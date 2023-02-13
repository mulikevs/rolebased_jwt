# ROLE BASED API WITH SPRING BOOT

A role based spring boot application with jwt authenticated REST APIs, with a mysql database

##### Requirements
For building and running the application you need:

* JDK 11
* Maven
* MySql

##### Running the application locally
There are several ways to run a Spring Boot application on your local machine. One way is to execute the main method in the com.samdev.mulikevs.rolebased_jwt.RolebasedJwtApplication class from your IDE.

Alternatively you can use the Spring Boot Maven plugin like so:

Build the project using ``` mvn clean install ```
Run using ``` mvn spring-boot:run ```
The application is accessible via localhost:8080


##### ROLES
The API has the below ROLES;
* USER,
* ADMIN,
* API

###### API Credentials
* USER
> email: user@test.com
> password: test123

* ADMIN
> email: admin@test.com
> password: test123

* API
> email: api@test.com
> password: test123



