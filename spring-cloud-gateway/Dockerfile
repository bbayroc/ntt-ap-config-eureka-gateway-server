FROM amazoncorretto:11-alpine-jdk
MAINTAINER bayro

COPY target/spring-cloud-gateway-0.0.1-SNAPSHOT.jar /gateway.jar
ENTRYPOINT ["java","-jar","/gateway.jar"]

#docker build -t UX-Demo-img .
#docker run -dp 8070:8070 UX-Demo-img

