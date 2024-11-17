FROM openjdk:21-jdk-slim
ARG JAR_FILE=build/libs/eureka-server-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} eureka-server.jar
WORKDIR /eureka-server
ENTRYPOINT ["java","-jar","/eureka-server.jar"]
EXPOSE 8761
