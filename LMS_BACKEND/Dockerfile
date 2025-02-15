# Use OpenJDK 17 as the base image
FROM openjdk:17-jdk

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/lms-docker.jar /app/lms-docker.jar

# Expose the application port
EXPOSE 8080

# Command to run the JAR file
CMD ["java", "-jar", "/app/lms-docker.jar"]
