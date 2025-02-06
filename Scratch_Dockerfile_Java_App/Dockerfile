# Start from scratch (empty image)
FROM scratch

WORKDIR /app
# Copy the JRE files from a pre-built JRE
COPY jre /app/jre

# Copy the JAR file into the container
COPY main.jar /app/main.jar

# Set the entrypoint to run the Java application
CMD ["/app/jre/bin/java", "-version"]
