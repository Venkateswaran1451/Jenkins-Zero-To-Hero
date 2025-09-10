
# Use official OpenJDK 21 base image
FROM eclipse-temurin:21-jdk

# Set working directory in container
WORKDIR /app

# Copy your application JAR (replace with your JAR name)
COPY target/spring-boot-web.jar app.jar

# Expose port (optional, if your app uses a port)


# Command to run the JAR
ENTRYPOINT ["java", "-jar", "app.jar"]
