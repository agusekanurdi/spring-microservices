FROM openjdk:8-jdk-alpine

ADD target/organization-service-1.0-SNAPSHOT.jar /

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/organization-service-1.0-SNAPSHOT.jar"]