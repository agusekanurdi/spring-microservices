FROM openjdk:8-jdk-alpine

ADD target/auth-service-1.0-SNAPSHOT.jar /

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/auth-service-1.0-SNAPSHOT.jar"]