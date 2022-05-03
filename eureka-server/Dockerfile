FROM amazoncorretto:11-alpine-jdk
MAINTAINER bayro
COPY target/eureka-server-0.0.1-SNAPSHOT.jar  /eureka.jar
ENTRYPOINT ["java","-jar","/eureka.jar"]

#docker build -t eureka-img .
#docker run -dp 8090:8090 eureka-img
#docker run --name=eureka --network=host -p 8090:8090 eureka-img

