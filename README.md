# Spring Boot Docker Demo
A Dockerized Spring Boot application showcasing DevOps skills.

## Features
- Simple REST endpoint at `/hello`
- Multi-stage Dockerfile for efficient builds

## How to Run
1. Clone this repo.
2. Run `docker build -t spring-boot-docker-demo .` to build the image.
3. Run `docker run -d -p 8080:8080 spring-boot-docker-demo` to start the container.
4. Visit `http://localhost:8080/hello` or use `curl`.

## Built With
- Spring Boot (Java)
- Docker
- Maven