Maven repository on github
===========================

use example:

> Maven repository

```xml

<repositories>
       <repository>
           <id>github-maven-repo</id>
           <url>https://raw.githubusercontent.com/bonashen/mvn-repo/master/</url>
       </repository>
 </repositories>

 ```

> Dependency

```xml
   <!-- for smtp server -->
   <dependency>
        <artifactId>smtp-core</artifactId>
        <groupId>org.mailster</groupId>
        <version>1.0.0-M3</version>
    </dependency>
    <!-- for Pop3 Server -->
    <dependency>
      <groupId>com.bona.server</groupId>
      <artifactId>POP3-Server-Core</artifactId>
      <version>0.1</version>
    </dependency>
```
