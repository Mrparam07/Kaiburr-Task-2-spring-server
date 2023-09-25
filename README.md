# Kaiburr-Task-2-spring-server


### Prerequisites

- Java
- Maven
- Spring Boot (Framework)
- MongoDB

### Dependencies

- **Spring Boot Starter Data MongoDB**
- **Spring Boot Starter Web**
- **Spring Boot Starter Tomcat**
- **SpringFox Swagger2**
- **SpringFox Swagger UI**
- **Jackson Datatype ThreeTenBP**
- **Bean Validation API Support**
- **Spring Boot Starter Test**
- **Jakarta XML Binding API**

#### Build using [Online Swagger Editor](http://editor.swagger.io/) :: swagger.yaml 

| Endpoint Description       | HTTP Method | Endpoint                             |
|---------------------------|-------------|--------------------------------------|
| Create a Server           | PUT         | `/servers/createServer`              |
| - Accepts "server" object in JSON format in the request body.        |             |                                      |
| Get Servers               | GET         | `/servers/getServer`                 |
| - Returns a list of "server" objects.                 |             |                                      |
| Get Server by ID          | GET         | `/servers/getServer?id=<ID>`         |
| - Returns a "server" object matching with ID.         |             |                                      |
| Get Servers by Name       | GET         | `/servers/getServer?name=<Name>`     |
| - Returns a list of "server" objects matching with Name. |             |                                      |
| Delete Server             | DELETE      | `/servers/deleteServer?id=<ID>`      |
| - Deletes a "server" object matching with ID.         |             |                                      |

## Consuming APIs

A SwaggerUI is generated automatically at `http://127.0.0.1:8080/servers/` which Documentsthe API and gives UI to consume the same.

### Screenshots

![SwaggerEditor](https://github.com/Mrparam07/Kaiburr-Assignment/blob/main/Task-2/Screenshots/SwaggerEditorTask2.png)

![SwaggerDoc](https://github.com/Mrparam07/Kaiburr-Assignment/blob/main/Task-2/Screenshots/SwaggerUITask2Home.png)

![SwagGenServ](https://github.com/Mrparam07/Kaiburr-Assignment/blob/main/Task-2/Screenshots/SwaggerUIGetAllServerTask2.png)

![createServer](https://github.com/Mrparam07/Kaiburr-Assignment/blob/main/Task-2/Screenshots/SwaggerUITask2.png)

![deleteServer](https://github.com/Mrparam07/Kaiburr-Assignment/blob/main/Task-2/Screenshots/SwaggerUIDeleteServerTask2.png)

### Swagger generated server

Spring Boot Server 

### Overview
This server is generated using swagger-codegen and the OpenAPI-Spec. It demonstrates building a Swagger-enabled server in Java using the Spring Boot framework, with springfox as the underlying library for integrating Swagger.

To start the server as a simple Java application, navigate to http://localhost:8080/
