# Use a lightweight base image
FROM alpine:latest

# Copy a simple script into the root directory of the container
COPY hello.sh /hello.sh

# Make the script executable
RUN chmod +x /hello.sh

# Define the command to run when the container starts
CMD ["/hello.sh"]
