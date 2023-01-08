# Microservices with Spring Cloud Demo Project

## Run keycloak
docker-compose up -d

## Steps to configure keycloak

- Create a realm with the name **spring-cloud-microservices** 
- Create a client with the name **spring-cloud-microservices-client**
- Copy the client secret and paste it into the **application.yml** file in the **client-secret** property