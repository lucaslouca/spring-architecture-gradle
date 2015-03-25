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

Notes: 
* You may need <a href="http://marketplace.eclipse.org/content/gradle-integration-eclipse-44" target="_blank">Gradle Integration for Eclipse</a>
* If you are using <a href="https://www.jetbrains.com/idea/" target="_blank">IntelliJ IDEA</a> make sure to replace ``apply plugin: 'eclipse'`` with ``apply plugin: 'idea'`` in the **build.gradle** file located in **spring-app**.

###Building
You can run:

```
gradle build
```

Or if you are behind a proxy:
```
gradle -Dhttp.proxyHost=proxy.address -Dhttp.proxyPort=80 -Dhttp.proxyUser=myusername -Dhttp.proxyPassword=mypassword build
```

###References
<a href="http://www.gradle.org/docs/current/userguide/java_plugin.html" target="_blank">Gradle Java plugin</a>
<a href="http://www.gradle.org/docs/current/userguide/maven_plugin.html" target="_blank">Gradle Maven plugin</a>
<a href="http://www.gradle.org/docs/current/userguide/eclipse_plugin.html" target="_blank">Gradle Eclipse plugin</a>
<a href="http://www.gradle.org/docs/current/userguide/idea_plugin.html" target="_blank">Gradle Idea plugin</a>
