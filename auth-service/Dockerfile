FROM openjdk:21-jdk-slim
ARG JAR_FILE=build/libs/auth-service-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} auth-service.jar
WORKDIR /app
ENTRYPOINT ["java", "-jar", "/auth-service.jar"]
EXPOSE 8082
