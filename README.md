# goondle
Google Java API Client Services as single osgi compatible bundle

https://developers.google.com/api-client-library/java

google-api-client version: 2.4.0

# maven

## repository

```
    <repository>
        <id>krybrig-public</id>
        <name>Krybrig Public Repository</name>
        <url>https://app.krybrig.org/maven/repository/public/</url>
    </repository>
```

## dependency

```
    <dependency>
        <groupId>org.krybrig</groupId>
        <artifactId>goondle</artifactId>
        <version>1.2.1</version>
    </dependency>
```

## build

mvn package install

## release

mvn release:prepare
mvn release:perform
