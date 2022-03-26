# Microservice Spring

## Basic study project of microservice architecture pattern in Spring Cloud (development environment):

- use of two microservices (product-catalog and shopping-cart), each accessing different data source (Elasticsearch and Redis);
- these microservices are compatible in a code structure, making theis maintenance much easier;
- implemented the Config Server, with the mais role of distributing configuration to all microservices, fetching the configurations on GitHub;
- implemented Service Discovery, another essential component of the microservice architecture pattern that has the service catalog, knows which service is on which port, etc. and can also be used as a load balancer;
- implemented the Gateway, which helps to expose the system to the front end (web or mobile).

### Configurations used:

- Java 11]
- Gradle Project
- Docker with Elasticsearch(6.6.2) and Redis(3.0.1)
- Spring Cloud Netflix Eureka Server
- Eureka Discovery Client
- Spring Boot Actuator
- Spring Web
- Spring Cloud Config Server
