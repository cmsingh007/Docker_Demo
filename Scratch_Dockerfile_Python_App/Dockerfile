# Use scratch as the base image
FROM scratch

WORKDIR /app

# Copy the statically compiled binary into the container
COPY dist/app /app

# Set the command to run the app
CMD ["/app"]

