# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the Java HelloWorld application to the container
COPY HelloWorld.java .

# Compile the Java HelloWorld application
RUN javac HelloWorld.java

# Run the HelloWorld application
CMD ["java", "HelloWorld"]
