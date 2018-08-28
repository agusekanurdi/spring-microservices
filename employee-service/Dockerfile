FROM openjdk:8-jdk-alpine

ADD target/employee-service-1.0-SNAPSHOT.jar /

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/employee-service-1.0-SNAPSHOT.jar"]