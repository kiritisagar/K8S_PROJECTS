# Use an official NGINX runtime as a parent image
FROM nginx:latest

# Copy custom NGINX configuration file to the container
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80 (default NGINX port)
EXPOSE 80

# Command to start NGINX when the container starts
CMD ["nginx", "-g", "daemon off;"]

