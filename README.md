# goondle
Google Java API Client Services as single osgi compatible bundle

https://developers.google.com/api-client-library/java

google-api-client version: 2.6.0

# maven

## repository

```
    <repository>
        <id>krybrig-repository-public</id>
        <name>mvn.kry.ovh</name>
        <url>https://mvn.kry.ovh/public</url>
    </repository>
```

## dependency

```
    <dependency>
        <groupId>org.krybrig</groupId>
        <artifactId>goondle</artifactId>
        <version>1.2.2</version>
    </dependency>
```

## build

mvn package install

## release

mvn release:prepare
mvn release:perform
