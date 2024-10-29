# Use an official OpenJDK as a base image
FROM openjdk:17-jdk-alpine

# Set the working directory in the container
WORKDIR /app

COPY build/libs/simple_db_app-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
