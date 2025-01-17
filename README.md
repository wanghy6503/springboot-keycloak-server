# Keycloak Server Embedded in a Spring Boot Application

This project provies an embedded [Keycloak](https://www.keycloak.org) server running on a [Spring Boot](https://spring.io/projects/spring-boot) application.

_Based on this post from [Baeldung](https://www.baeldung.com/keycloak-embedded-in-spring-boot-app)._

## Features

- Fully standalone Keycloak server running on embedded Tomcat;
- Added a custom theme with providers only login screen.

## Compatibility

| Version | Java | Keycloak | Spring Boot | RESTEasy | Infinispan | Liquibase |
| - | - | - | - | - | - | - |
| 3.0.0 | 17 | 21.0.0 | 2.7.9 | 4.7.7.Final | 14.0.6.Final | 4.16.1 |
| 3.0.2 | 17 | 21.0.2 | 2.7.9 | 4.7.7.Final | 14.0.6.Final | 4.16.1 |
| 3.1.0 | 17 | 21.1.1 | 2.7.11 | 4.7.7.Final | 14.0.8.Final | 4.20.0 |
| 4.0.0 | 17 | 22.0.5 | 3.1.5 | 6.2.4.Final | 14.0.19.Final | 4.23.2 |

* Removed older versions from compatibility table keeping last 2 major version. For olders, check the [tags](https://github.com/suchorski/springboot-keycloak-server/tags) section.

## Configurations

You can customize the server by changing the `application.yml` file inside `resources` folder.

## Building

You can clone this repo and build it using the [Maven](https://maven.apache.org/).

```bash
$ git clone https://github.com/suchorski/springboot-keycloak-server
$ cd springboot-keycloak-server
$ mvn package
$ java -jar target/server-4.0.0.jar
```

# Contribution

Feel free to contribute with us.
