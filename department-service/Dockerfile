FROM openjdk:8-jdk-alpine

ADD target/department-service-1.0-SNAPSHOT.jar /

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/department-service-1.0-SNAPSHOT.jar"]