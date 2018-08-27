FROM openjdk:8-jdk-alpine

ADD target/discovery-service-1.0-SNAPSHOT.jar /

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/discovery-service-1.0-SNAPSHOT.jar"]