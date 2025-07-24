# Use a lightweight Nginx base image
FROM alpine:latest

# Copy the local index.html file into the Nginx web root directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80 to allow incoming HTTP connections
EXPOSE 80

# Start Nginx when the container launches
CMD ["nginx", "-g", "daemon off;"]
