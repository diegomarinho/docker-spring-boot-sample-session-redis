# docker-spring-boot-sample-session-redis

This sample application in Docker.

* Spring Boot
* Spring Session
* Java 8
* Docker-Compose
* Redis

#### Build docker image

```
mvn package
mvn package docker:build
```

#### Run the application

```
docker-compose up
```


#### Test the application

```
http://localhost:8080/
```