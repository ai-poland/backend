# AgroAdvisor Server

## Introduction

This is a Spring Boot-based server project. The project aims to provide a backend API for a web/mobile application. With Spring Boot, the server is easy to configure, fast to start, and its development is flexible and scalable.

## Technologies

 - Java: Main programming language.
- Spring Boot: Framework for rapid development of web applications.
- Spring Data JPA: For database communication.
- PostgreSQL: Database for storing information.
- Maven: Build tool for the project.

## Installation and Running

### Requirements:

- Java 23

- Maven

- PostgreSQL

### Installation Steps:

Clone the project repository:
```sh
git clone https://github.com/ai-poland/agroadvisor-server.git
```
Then configure the PostgreSQL database:

username: `postgres`<br>
password: `postgres`<br>
port: `5432`


You can also use your own configuration, but remember to update the [application.properties](src/main/resources/application.properties) file.


Now you can run the application like a regular maven project!