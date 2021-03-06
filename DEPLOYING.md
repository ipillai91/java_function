# Deploying

## Prerequisites

- [curl](https://curl.se/download.html)
- [pack](https://buildpacks.io/docs/tools/pack/) >= `0.23.0`
- [func](https://github.com/knative-sandbox/kn-plugin-func/blob/main/docs/installing_cli.md)

## Building your function

You can build your function using our provided builder, which already includes buildpacks and an invoker layer:

```
pack build java-function --path . --builder ghcr.io/vmware-tanzu/function-buildpacks-for-knative/functions-builder:0.0.10
```

Where `java-function` is the name of your runnable function image, later used by Docker.

## Local Deployment

### Docker

This assumes you have Docker Desktop properly installed and running.

With Docker Desktop running, authenticated, and the ports (default `8080`) available:

```
docker run -it --rm -p 8080:8080 java-function
```

## Testing

With our functions, you should see some HTML or sample text returned indicating a success.

### HTTP

After deploying your function, you can interact with the function by running:

```
curl -w'\n' localhost:8080/hire \
 -H "Content-Type: application/json" \
 -d '{"firstName":"John", "lastName":"Doe"}' -i
 ```

> Where `/hire` as a path invokes that specific function

### CloudEvents

If you'd like to test this function, you may use this CloudEvent saved as `cloudevent.json`:

```
{
    "specversion" : "1.0",
    "type" : "hire",
    "source" : "https://spring.io/",
    "id" : "A234-1234-1234",
    "datacontenttype" : "application/json",
    "data": {
        "firstName": "John",
        "lastName": "Doe"
    }
}
```

> NOTE: that you should change the contents of the CloudEvent you're testing against as you update the function.

After [deploying](https://github.com/vmware-tanzu/function-buildpacks-for-knative/blob/main/DEPLOYING.md) your function as an image, you can test with:

```
curl -X POST -H "Content-Type: application/cloudevents+json" -d @cloudevent.json http://localhost:8080
```

## TAP Deployment - Alpha

### Deploying to Kubernetes

> NOTE: The provided `config/workload.yaml` file uses the Git URL for this sample. When you want to modify the source, you must push the code to your own Git repository and then update the `spec.source.git` information in the `config/workload.yaml` file.


## Deploying to Kubernetes as a TAP workload with Tanzu CLI

You need to select the accelerator option `Include TAP deployment resources` when generating the project for the steps below to function.

When you are done developing your app, you can simply deploy it using:

```
tanzu apps workload apply -f config/workload.yaml
```

If you would like deploy the code from your local working directory you can use the following command:

```
tanzu apps workload create java-function -f config/workload.yaml \
  --local-path . \
  --source-image <REPOSITORY-PREFIX>/java-function-source \
  --type web
```

## Interacting with Tanzu Application Platform

Determine the URL to use for the accessing the app by running:

```
tanzu apps workload get java-function
```

> NOTE: This depends on the TAP installation having DNS configured for the Knative ingress.

After deploying your function, you can interact with the function by using:

> NOTE: Replace the <URL> placeholder with the actual URL.

### for HTTP

```
curl -w'\n' <URL>/hire \
 -H "Content-Type: application/json" \
 -d '{"firstName":"John", "lastName":"Doe"}' -i
 ```

> Where `/hire` as a path invokes that specific function

### for CloudEvents

If you'd like to test this function, you may use this CloudEvent saved as `cloudevent.json`:

```
{
    "specversion" : "1.0",
    "type" : "hire",
    "source" : "https://spring.io/",
    "id" : "A234-1234-1234",
    "datacontenttype" : "application/json",
    "data": {
        "firstName": "John",
        "lastName": "Doe"
    }
}
```

> NOTE: that you should change the contents of the CloudEvent you're testing against as you update the function.

```
curl -X POST -H "Content-Type: application/cloudevents+json" -d @cloudevent.json <URL>
```
