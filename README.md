# Core Microservices Parent POM

Parent POM providing dependency and plugin management for all Core Microservices modules.

## Usage

Add as parent in your service POM:

```xml
<parent>
    <groupId>com.corems</groupId>
    <artifactId>parent</artifactId>
    <version>0.0.1-SNAPSHOT</version>
</parent>
```

## Managed Dependencies

- Spring Boot 4.0.0
- Spring Cloud 2024.0.0
- Lombok (edge-SNAPSHOT)
- OpenAPI Generator 7.17.0
- Jackson Databind Nullable
- Swagger Core Jakarta

## Managed Plugins

- maven-compiler-plugin (Java 25)
- maven-surefire-plugin
- maven-dependency-plugin
- openapi-generator-maven-plugin
- spring-boot-maven-plugin

## Installation

```bash
mvn clean install
```

This installs the parent POM to your local Maven repository, making it available for child modules.

## Requirements

- Java 25+
- Maven 3.9.3+
