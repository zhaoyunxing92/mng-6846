# mng-6846

[MNG-6846](https://github.com/apache/maven/tree/MNG-6846)

## Problem of repetition step

* mvn clean package -pl goods -am -Drevision=2.1

* error

```log
[ERROR] Failed to execute goal on project goods: Could not resolve dependencies for project io.github.sunny:mode01:jar:2.1: Failed to collect dependencies at org.apac
he.dubbo:dubbo-spring-boot-starter:jar:2.7.3: Failed to read artifact descriptor for org.apache.dubbo:dubbo-spring-boot-starter:jar:2.7.3: Could not find artifact org.
apache.dubbo:dubbo-dependencies-bom:pom:2.1 in central (https://repo.maven.apache.org/maven2) -> [Help 1]
```


