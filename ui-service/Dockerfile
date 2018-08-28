FROM openjdk:8-jdk-alpine

ADD target/ui-service-1.0-SNAPSHOT.jar /

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/ui-service-1.0-SNAPSHOT.jar"]