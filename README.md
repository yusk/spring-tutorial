# README

https://spring.io/guides/gs/spring-boot/

## setup

```bash
brew tap pivotal/tap
brew install springboot
```

## bash

```bash
./gradlew bootRun
curl localhost:8080
curl localhost:8080/actuator/health
curl -X POST localhost:8080/actuator/shutdown

spring run app.groovy
```