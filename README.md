# fw-boot-sample

Demo project for Spring Boot.

## Project Overview
This project demonstrates a basic Spring Boot application setup using Maven. It is intended as a sample or starting point for building web applications with Spring Boot.

## Requirements
- Java 17 or higher
- Maven 3.6+

## Dependencies
The project uses the following main dependencies:

- **Spring Boot Starter Web**  
  Provides core web development features, including RESTful APIs and embedded Tomcat server.
  - `org.springframework.boot:spring-boot-starter-web`

- **Spring Boot Starter Test**  
  Provides testing libraries and utilities for Spring Boot applications. (Test scope only)
  - `org.springframework.boot:spring-boot-starter-test`

## Getting Started
To build and run the project:

```sh
mvn clean install
mvn spring-boot:run
```

## Reference Documentation
- [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
- [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/3.5.0/maven-plugin)
- [Create an OCI image](https://docs.spring.io/spring-boot/3.5.0/maven-plugin/build-image.html)
- [Spring Web](https://docs.spring.io/spring-boot/3.5.0/reference/web/servlet.html)

## Guides
- [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
- [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
- [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

## Notes
- The original package name `com.example.fw-boot-sample` was changed to `com.example.fw_boot_sample` due to Java package naming conventions.
- The project inherits from a parent POM (`freshworks-boot-starter-parent`). If you change the parent, review the `<license>` and `<developers>` overrides in the POM.