FROM openjdk:8-jdk-alpine

ADD target/config-service-1.0-SNAPSHOT.jar /

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/config-service-1.0-SNAPSHOT.jar"]