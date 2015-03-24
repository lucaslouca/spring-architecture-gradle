# spring-architecture-gradle

This is the gradle verson of <a href="https://github.com/lucaslouca/spring-architecture" target="_blank">spring-architecture</a> project.


###How to Import into Eclipse
* **File** -> **Import...** -> **Gradle** -> **Gradle Project**
* Click **Next**
* Click **Browse...** for the **Root Directory**
* Select and open **spring-app**
* Click **Build Model**
* Select all projects
* Click **Finish**

###Building
You can run:

>```
>gradle build
>```

> Or if you are behind a proxy:
>```
>gradle -Dhttp.proxyHost=proxy.address -Dhttp.proxyPort=80 -Dhttp.proxyUser=myusername -Dhttp.proxyPassword=mypassword build
>```
