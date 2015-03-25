# spring-architecture-gradle

This is the <a href="https://www.gradle.org" target="_blank">gradle</a> version of <a href="https://github.com/lucaslouca/spring-architecture" target="_blank">spring-architecture</a> project.


###How to Import into Eclipse
* **File** -> **Import...** -> **Gradle** -> **Gradle Project**
* Click **Next**
* Click **Browse...** for the **Root Directory**
* Select and open **spring-app**
* Click **Build Model**
* Select all projects
* Click **Finish**
* Run ``gradle clean`` and ``gradle assemble`` on the **spring-app** project

Note: You may need <a href="http://marketplace.eclipse.org/content/gradle-integration-eclipse-44" target="_blank">Gradle Integration for Eclipse</a>

###Building
You can run:

```
gradle build
```

Or if you are behind a proxy:
```
gradle -Dhttp.proxyHost=proxy.address -Dhttp.proxyPort=80 -Dhttp.proxyUser=myusername -Dhttp.proxyPassword=mypassword build
```
