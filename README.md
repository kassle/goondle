# goondle
Google Java API Client Services as single osgi compatible bundle

https://developers.google.com/api-client-library/java

google-api-client version: 2.9.0

# maven

## repository

```
    <repository>
        <id>rayslan-public</id>
        <name>Rayslan Maven Repository</name>
        <url>https://repo.rayslan.com/maven/public</url>
    </repository>
```

## dependency

```
    <dependency>
        <groupId>org.krybrig</groupId>
        <artifactId>goondle</artifactId>
        <version>1.2.4</version>
    </dependency>
```

## build

mvn package install

## release

mvn release:prepare
mvn release:perform
