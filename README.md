# spring-rest-pagination
Demonstrates how to implement pagination for a Spring Boot REST API, running against a Mongo database.

## Usage Guidelines 

* Clone this repository 

`git clone https://github.com/NabilCC/spring-rest-pagination`

* Switch directory

`cd spring-rest-pagination`

* Start the application

`./gradlew bootRun`

* Get the first page with size = 5 elements

`curl http://localhost:8080/customer?page=0&size=5`

* Get the second page with size = 10 elements

`curl http://localhost:8080/customer?page=2&size=10`

* Get the first page of size = 20

`curl http://localhost:8080/customer?page=1&size=20`
