Download this repo to your maven local repository. Here is an example path on my computer


```
2.6.0-SNAPSHOT$ pwd
/Users/batbat/.m2/repository/org/apache/beam/beam-sdks-java-extensions-google-cloud-platform-core/2.6.0-SNAPSHOT
```

```
2.6.0-SNAPSHOT$ ls
beam-sdks-java-extensions-google-cloud-platform-core-2.6.0-SNAPSHOT-javadoc.jar
beam-sdks-java-extensions-google-cloud-platform-core-2.6.0-SNAPSHOT-sources.jar
beam-sdks-java-extensions-google-cloud-platform-core-2.6.0-SNAPSHOT-test-sources.jar
beam-sdks-java-extensions-google-cloud-platform-core-2.6.0-SNAPSHOT-tests.jar
beam-sdks-java-extensions-google-cloud-platform-core-2.6.0-SNAPSHOT.jar
beam-sdks-java-extensions-google-cloud-platform-core-2.6.0-SNAPSHOT.pom
maven-metadata-local.xml
```

Finally, add it to your `pom.xml`

```
<dependency>
    <groupId>org.apache.beam</groupId>
    <artifactId>beam-sdks-java-extensions-google-cloud-platform-core</artifactId>
    <version>2.6.0-SNAPSHOT</version>
</dependency>
```
