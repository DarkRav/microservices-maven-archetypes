microservices-maven-archetypes
======================================

Summary
-------
Catalog of maven archetypes for microservices to simplify its creation.

Prerequisites
-------------

- JDK 8
- Maven 3

Ecosystem result
-------
![Alt text](docs/archetypes.jpg?raw=true "Ecosystem")





General installation instructions
-------------
Two installation ways:

### Local

1. Clone repository
```bash
git clone https://github.com/rafabc/microservices-maven-archetypes.git
```
2. In console go to each archetype path
```bash
cd microservices-maven-archetypes/[archetype-path]
```
3. run next commands
```bash
mvn install 	#for each archetype
mvn install archetype:update-local-catalog
mvn archetype:crawl
```

### Hosted

1. Clone repository
```bash
git clone https://github.com/rafabc/microservices-maven-archetypes.git
```
2. Install the archetypes in your maven repository
3. This repository provide a catalog file, with it you can update your hosted catalog and then use it where you want.


Creation projects instructions
---
- [Spring Cloud Config Server](./archetype-config-server/)
- [Eureka](./archetype-eureka/)
- [Spring Boot Admin](./archetype-springbootadmin/)
- [Zuul](./archetype-zuul/)
- [Spring microservice](./archetype-microservice-spring/)
