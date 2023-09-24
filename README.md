# Task 2 : Swagger Codegen
## Implementation of Swagger with SpringBoot

* Added dependencies for swagger in existing Project of task 1.
* Created a new file ```SwaggerConfig.java``` and annotted the class with ```@EnableSwagger2``` Annotation.

### Testing of Swagger on localhost

* Tested swagger on localhost using url ```http://127.0.0.1:2017/swagger-ui.html#```

## Features
- Generate a REST API server from a Swagger/OpenAPI definition.
- Implement CRUD (Create, Read, Update, Delete) operations for API endpoints.
- Test the API using Postman, Curl, or other HTTP clients.

## Technologies Used
- Swagger/OpenAPI
- Java
- Spring Boot
- MongoDB

## Requirements
- Access to Swagger Editor: https://editor.swagger.io/
- Java development environment (JDK, IDE)
- Maven or Gradle build tool (if using Spring Boot)
- MongoDB
- Postman

## How the Task is Done

1. Swagger Definition Creation:

- Created a Swagger/OpenAPI definition for the REST API at https://editor.swagger.io/.
- Defined API endpoints, request/response parameters, and saved the Swagger definition in YAML format.

### Screenshots
![Screenshot](https://drive.google.com/uc?id=1ICGEwY6b3Cp8da3DYcEvgf0Mwab3B6I1)

![Screenshot](https://drive.google.com/uc?id=1lVqavvl4s1kabvO321i_FdYX1Vetmsnk)

2. Server Code Generation:

- Visited the Swagger Codegen repository at https://github.com/swagger-api/swagger-codegen.
- Followed provided documentation to generate the server stub for the chosen Java-based server framework.
- Utilized the command-line tool as instructed, resulting in a project structure containing API controllers and models.

3. Functionality Implementation:

- Opened the generated server code project in the Java IDE IntelliJ.
- Located the API controller classes for the defined endpoints.
- Implemented functionality for each endpoint based on the Swagger definition.
- Created business logic to handle incoming HTTP requests and responses.

#### Note: Had come difficulties in completing the functionality implementation. Working on it...

With these steps, the task of creating a REST API using Swagger Codegen is covered.

Thank You !!!
