Maven repository on github
===========================

use example:

> Maven repository

```xml

<repositories>
       <repository>
           <id>github-maven-repo</id>
           <url>https://raw.githubusercontent.com/bonashen/mvn-repo/tree/master/</url>
       </repository>
 </repositories>

 ```

> Dependency

```xml
   <dependency>
        <artifactId>smtp-core</artifactId>
        <groupId>org.mailster</groupId>
        <version>1.0.0-M3</version>
    </dependency>
```
