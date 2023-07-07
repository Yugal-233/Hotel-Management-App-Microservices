FROM openjdk:17
EXPOSE 8081
ADD ./target/user-service-microservice.jar user-service-microservice.jar
ENTRYPOINT ["java","-jar","/user-service-microservice.jar"]