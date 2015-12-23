Squadron
========

Playing around with a webapp running in a docker container.

Java 8, Spring Boot 1.3.1, Gradle 2.9, Docker 1.9.1

How to build and start
----------------------
1. gradlew dockerBuildImage
2. docker run --name sqdr -d -P -it codecraft/squadron