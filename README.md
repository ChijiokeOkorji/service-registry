# Service Registry Microservice
The Service Registry Microservice is a simple application that acts as a registry for microservices in your architecture. It uses Eureka Server, a part of Spring Cloud Netflix, for service registration and discovery.

## Getting Started

### Prerequisites
- Java Development Kit (JDK) installed on your machine
- Apache Maven for building and managing dependencies

### Installation
1. Clone the repository:
```bash
git clone https://github.com/ChijiokeOkorji/service-registry.git
```
2. Navigate to the project directory:
```bash
cd service-registry
```
3. Build the project using Maven:
```bash
mvn clean install
```
4. You can optionally pass environment variables in the project configurations for the following:
```bash
# Port on which the application runs (default: 8761)
PORT

# Hostname for the service registry (default: localhost)
HOSTNAME
```
5. Run the application:
```bash
java -jar target/service-registry-0.0.1-SNAPSHOT.jar
```
6. Access the Eureka Server dashboard: Open a web browser and go to http://localhost:8761 (if you changed the default project configurations, you can replace this with the new URL)

## Documentation
For more information about how to use and configure the Service Registry Microservice, refer to the following resources:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web)
* [Eureka Server](https://docs.spring.io/spring-cloud-netflix/docs/current/reference/html/#spring-cloud-eureka-server)

## Additional Resources
Explore some additional guides to learn more about building microservices with Spring Boot and Spring Cloud:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Service Registration and Discovery with Eureka and Spring Cloud](https://spring.io/guides/gs/service-registration-and-discovery/)
