# Use the official OpenJDK image
FROM openjdk:11-jdk-slim

# Set the working directory
WORKDIR /app

# Copy the application JAR file into the container
COPY target/hello-world.jar /app/hello-world.jar

# Command to run the application
CMD ["java", "-jar", "hello-world.jar"]
