# Use the official OpenJDK 11 image as the base image
FROM openjdk:19-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the Spring Boot JAR file into the container
COPY ./build/libs/simple_docker_api-1.0-SNAPSHOT.jar app.jar

# Expose the port the Spring Boot application runs on
EXPOSE 8080

# Set the command to run the Spring Boot application
CMD ["java", "-jar", "app.jar"]


