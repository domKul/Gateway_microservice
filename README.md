### Gateway for microservice 

####  part (2) of microservices
* (1) [Eureka Server](https://github.com/domKul/EurekaServer_microservice)
* (2) [Gateway](https://github.com/domKul/Gateway_microservice)
* (3) [Notification service](https://github.com/domKul/Notification_microservice)
* (4) [Course service](https://github.com/domKul/CourseService_microservice)
* (5) [Student service](https://github.com/domKul/Students_microservice)

# Gateway Service

Gateway Service is a Spring Cloud component that serves as an entry point for your microservices architecture, handling routing and API composition.

## Running the Gateway Service

To run the Gateway Service, follow these steps:

1. Clone the project sources from the repository.

2. Run the program with IDE or use command `./mvnw spring-boot:run`

3. For using this gateway you need to use this url `http://localhost:9000` then the res of endpoitnts routs

Example: Insted of `http://localhost:8080/courses/courses` use `http://localhost:9000/course-service/courses`