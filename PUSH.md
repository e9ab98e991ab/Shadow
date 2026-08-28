# 发布maven 带版本号的
首先修改buildScripts/gradle/versions.properties中的 VERSION_CODE 和 VERSION_NAME 信息 
```shell 
PUBLISH_RELEASE=true ./gradlew publish
```