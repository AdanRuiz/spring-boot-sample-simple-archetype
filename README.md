# spring-boot-sample-simple-archetype
 
This is a simple springboot maven archetype.

## Install

``` shell
$ git clone https://github.com/AdanRuiz/spring-boot-sample-simple-archetype.git
$ cd spring-boot-sample-simple-archetype
$ mvn clean install
```

## Usage

```
mvn archetype:generate  -DarchetypeGroupId=com.github.adanruiz -DarchetypeArtifactId=spring-boot-sample-simple-archetype -DarchetypeVersion=1.1.1.RELEASE -DgroupId=com.tlg     -DartifactId=person -Dversion=1.0.0-SNAPSHOT -DinteractiveMode=false
```