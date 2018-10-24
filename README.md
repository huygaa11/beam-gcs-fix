This patch lets you use `beam-sdks-java-extensions-google-cloud-platform-core` package that fixed hanging `Unexpected end of file` error.

To use, download the snapshot folder from this repo to your maven local repository under beam folder. Here is an example path on my computer:


```
beam-sdks-java-extensions-google-cloud-platform-core$ pwd
/Users/batbat/.m2/repository/org/apache/beam/beam-sdks-java-extensions-google-cloud-platform-core
```

This snapshot should be placed as shown in this command. In this case, I am using 2.7.0-SNAPSHOT

```
beam-sdks-java-extensions-google-cloud-platform-core$ ls
2.7.0-SNAPSHOT/
```

Finally, add it to your `pom.xml`. Make sure to use the correct `2.x.0` version that matches your beam version.

```
<dependency>
    <groupId>org.apache.beam</groupId>
    <artifactId>beam-sdks-java-extensions-google-cloud-platform-core</artifactId>
    <version>2.7.0-SNAPSHOT</version>
</dependency>
```

And run your pipeline!
