# Accelerator Log

## Options
```json
{
  "gitBranch" : "main",
  "gitRepository" : "https://github.com/trisberg/my-fun",
  "javaVersion" : "1.8",
  "liveUpdateIDESupport" : true,
  "projectName" : "my-fun",
  "sourceRepositoryPrefix" : "gcr.io/cf-sandbox-trisberg"
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
┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, AcceleratorInvocation, AcceleratorInvocation)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Exclude)
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties matched [**] -> included
┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [README.md]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [README.md] -> included
┃ ┃ ┃ ┗ ┗ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [README.md] -> included
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [more-fun->my-fun]
┃ ┃ ┃ ┏ README (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(Append))
┃ ┃ ┃ ┃ README.merge (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ README.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ ┃ README.merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[0].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.merge.transformations[0].sources[0].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗  Info Will replace [more-fun template repo->my-fun]
┃ ┃ ┃ ┗ ╺ README.merge.transformations[1] (UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3] (AcceleratorInvocation)
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].merge (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/*]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug live-update/DEPLOYING.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[0].<combo>.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md matched [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug live-update/DEPLOYING.md matched [README.md, DEPLOYING.md, LICENSE, live-update/**, config/**l, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug live-update/DEPLOYING.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [https://git.example.com/my-repo->https://github.com/t...(truncated)]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [my-project->my-fun]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [main->main]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [catalog/catalog-info.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/catalog-info.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug live-update/DEPLOYING.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[2].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[2].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [my-project->my-fun]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#liveUpdateIDESupport) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#liveUpdateIDESupport) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug live-update/DEPLOYING.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[3].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[3].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [my-project->my-fun]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[3].<combo>.transformations[1].transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [dev.local->gcr.io/cf-sandbox-tr...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#liveUpdateIDESupport) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#liveUpdateIDESupport) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [live-update/DEPLOYING.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [live-update/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug live-update/DEPLOYING.md matched [live-update/DEPLOYING.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[4].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[4].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [my-project->my-fun]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[4].<combo>.transformations[1].transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [dev.local->gcr.io/cf-sandbox-tr...(truncated)]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[4].<combo>.transformations[1].transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'live-update/DEPLOYING.md' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.md, folder=live-update/, filename=DEPLOYING.md, g0=live-update/DEPLOYING.md, g1=live-update/, g2=DEPLOYING.md, g3=DEPLOYING.md, g4=.md} and was rewritten to 'DEPLOYING.md'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (!#liveUpdateIDESupport) evaluated to false
┃ ┃ ┃ ┃ ┗ ┗ null ()
┃ ┃ ┃ ┗ ╺ engine.transformations[0].merge.transformations[0].sources[3].merge.transformations[1] (UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4] (AcceleratorInvocation)
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[4].merge (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[0].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[0].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace regex '<java.version>.*<' with '<java.version>1.8<'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [build.gradle]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/helloapp/HelloAppApplication.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/helloapp/HelloAppApplicationTests.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗  Info Will replace regex 'sourceCompatibility = .*' with 'sourceCompatibility ...(truncated)'
┃ ┃ ┗ ┗ ╺ engine.transformations[0].merge.transformations[0].sources[4].merge.transformations[1] (UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[1] (UniquePath)
┃ ┃ ┃ Debug Multiple representations for path 'mvnw', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'mvnw.cmd', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/example/helloapp/HelloAppApplicationTests.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'pom.xml', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path '.mvn/wrapper/maven-wrapper.jar', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path '.mvn/wrapper/maven-wrapper.properties', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/application.properties', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/helloapp/HelloAppApplication.java', will use the one appearing last 
┃ ┗ ┗ Debug Multiple representations for path '.mvn/wrapper/MavenWrapperDownloader.java', will use the one appearing last 
┗ ╺ engine.transformations[1] (UniquePath)
```
