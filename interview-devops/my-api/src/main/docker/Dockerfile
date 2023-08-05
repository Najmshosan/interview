# Use an official OpenJDK runtime as a base image
# Use an official OpenJDK runtime as a base image
FROM openjdk:12-alpine

# Set the working directory to /app
# WORKDIR /app/my-api

# Copy the executable jar into the container at /app
COPY target/my-api-*.jar ./my-api.jar
# ADD target/my-api-*.jar /app/my-api.jar

# Command to run the application
CMD ["java", "-jar", "/my-api.jar"]