# Accelerator Log

## Options
```json
{
  "buildType" : "maven",
  "gitBranch" : "main",
  "gitUrl" : "https://github.com/ipillai91/java_function.git",
  "includeTap" : true,
  "interfaceType" : "http",
  "projectName" : "java-function"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[0].include (Include)
┃ ┃ ┃ ┃  Info Will include [src/**, func.yaml, LICENSE, NOTICE, .gitignore]
┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug LICENSE matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┃ Debug NOTICE matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┃ Debug README.md didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug build.gradle didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/Hire.java didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug func.yaml matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug gradlew didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug mvnw didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug pom.xml didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug settings.gradle didn't match [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/functions/Hire.java matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java matched [src/**, func.yaml, LICENSE, NOTICE, .gitignore] -> included
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [README.md, DEPLOYING.md]
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md matched [README.md, DEPLOYING.md] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug NOTICE didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, DEPLOYING.md] -> included
┃ ┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/Hire.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug func.yaml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Hire.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [README.md, DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [my-java-fn->java-function]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃  Info Condition (#buildType == 'maven') evaluated to true
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[2].include (Include)
┃ ┃ ┃ ┃  Info Condition (#buildType == 'maven') evaluated to true
┃ ┃ ┃ ┃  Info Will include [.mvn/**, mvnw, mvnw.bat]
┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java matched [.mvn/**, mvnw, mvnw.bat] -> included
┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar matched [.mvn/**, mvnw, mvnw.bat] -> included
┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [.mvn/**, mvnw, mvnw.bat] -> included
┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug LICENSE didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug NOTICE didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug README.md didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug build.gradle didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/Hire.java didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug func.yaml didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug gradlew didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug mvnw matched [.mvn/**, mvnw, mvnw.bat] -> included
┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug pom.xml didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug settings.gradle didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/functions/Hire.java didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [.mvn/**, mvnw, mvnw.bat] -> excluded
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃  Info Condition (#buildType == 'maven' && #interfaceType == 'http') evaluated to true
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃  Info Condition (#buildType == 'maven' && #interfaceType == 'http') evaluated to true
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug NOTICE didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/Hire.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug func.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Hire.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [my-java-fn->java-function]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃  Info Condition (#buildType == 'maven' && #interfaceType == 'cloudevents') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃  Info Condition (#buildType == 'gradle') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃  Info Condition (#buildType == 'gradle') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[7] (Combo)
┃ ┃ ┃ ┃  Info Condition (#buildType == 'gradle' && #interfaceType == 'http') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[8] (Combo)
┃ ┃ ┃ ┃  Info Condition (#buildType == 'gradle' && #interfaceType == 'cloudevents') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[9] (Combo)
┃ ┃ ┃ ┃  Info Condition (#interfaceType == 'cloudevents') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[10] (Combo)
┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[10].<combo> (Chain)
┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[10].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug NOTICE didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/Hire.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug func.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Hire.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[10].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[10].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [https://github.com/sample-accelerators/java-functions-accelerator.git->https://github.com/i...(truncated), main->main, my-java-fn->java-function]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[10].<combo>.transformations[1].transformations[1] (RewritePath)
┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'config/workload.yaml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yaml, folder=config/, filename=workload.yaml, g0=config/workload.yaml, g1=config/, g2=workload.yaml, g3=workload.yaml, g4=.yaml} and was rewritten to 'config/workload.yaml'
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[11] (Combo)
┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[11].<combo> (Chain)
┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[11].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [catalog/catalog-info.yaml]
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug NOTICE didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/catalog-info.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug cloudevents/Hire.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/build.gradle didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/jar-assembly.xml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Employee.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/models/Person.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/pom.xml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug func.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/Hire.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/functions/models/Employee.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug src/main/java/functions/models/Person.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[11].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[11].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┗ ┗ ┗ ┗  Info Will replace [my-java-fn->java-function]
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
