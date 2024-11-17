FROM openjdk:21-jdk-slim
ARG JAR_FILE=build/libs/user-service-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} user-service.jar
WORKDIR /app
ENTRYPOINT ["java","-jar","/user-service.jar"]
EXPOSE 8090
