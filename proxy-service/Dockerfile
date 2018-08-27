FROM openjdk:8-jdk-alpine

ADD target/proxy-service-1.0-SNAPSHOT.jar /

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/proxy-service-1.0-SNAPSHOT.jar"]