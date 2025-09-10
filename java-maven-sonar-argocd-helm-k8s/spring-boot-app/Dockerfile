# Base image: Maven with Java 21 (Temurin)
FROM maven:3.9.6-eclipse-temurin-21

# Install Docker CLI
USER root
RUN apt-get update && \
    apt-get install -y docker.io && \
    rm -rf /var/lib/apt/lists/*

# Default workdir
WORKDIR /workspace

# Print versions for debugging
RUN java -version && mvn -v && docker --version

# Switch back to Jenkins-friendly user
CMD ["bash"]
