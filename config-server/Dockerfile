FROM amazoncorretto:11-alpine-jdk
MAINTAINER bayro
COPY target/config-server-0.0.1-SNAPSHOT.jar  /configserver.jar
ENTRYPOINT ["java","-jar","/configserver.jar"]

#docker build -t configserver-img .
##docker run -dp 8888:8888 configserver-img
#docker run --name=configserver --network=host -p 8888:8888 configserver-img
