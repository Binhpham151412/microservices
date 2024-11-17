FROM openjdk:21-jdk-slim
ARG JAR_FILE=build/libs/config-server-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} config-server.jar
WORKDIR /app
ENTRYPOINT ["java", "-jar", "/config-server.jar"]
EXPOSE 8888
