# java-dotenv

### This package has been renamed to [dotenv-kotlin](https://github.com/cdimascio/dotenv-kotlin)

<p align="left">
	<a href="https://github.com/cdimascio/dotenv-kotlin"><img src="https://raw.githubusercontent.com/cdimascio/dotenv-kotlin/master/assets/kotlin-dotenv-logo.png" alt="dotenv" width="250" /></a>
</p>

### Looking for a pure Java version, see [dotenv-java](https://github.com/cdimascio/dotenv-java)

<p align="left">
	<a href="https://github.com/cdimascio/dotenv-java"><img src="https://raw.githubusercontent.com/cdimascio/dotenv-java/master/assets/dotenv-java-logo.png" alt="dotenv-java" width="260" /></a>
</p>

### Why?

To avoid confusion. 

java-dotenv was implemented in Kotlin. This meant that Java-only users would end up pulling in some Kotlin deps. In order to keep the package size as small as possible for Java-only users, we've rewritten the dotenv core in Java. 

The [dotenv-java](https://github.com/cdimascio/dotenv-java) project contains the pure Java variant. It implements the same API as the original java-dotenv (with the exception of the Kotlin DSL

The [dotenv-kotlin](https://github.com/cdimascio/dotenv-kotlin) project is almost identical to the previous java-dotenv package. The only difference is that its core is provided by [dotenv-java](https://github.com/cdimascio/dotenv-java). It continues to provide functionality similar to before and includes the Kotlin DSL


### Latest versions of java-dotenv

The last version of java-dotenv is `5.2.2`. It is available on MavenCentral and JCenter

We recommend you use **dotenv-java** or **dotenv-kotlin** instead.

### Maven 
```xml
<dependency>
    <groupId>io.github.cdimascio</groupId>
    <artifactId>java-dotenv</artifactId>
    <version>5.2.2</version>
</dependency>
```

### Gradle

```groovy
implentation 'io.github.cdimascio:java-dotenv:5.2.2'
```
