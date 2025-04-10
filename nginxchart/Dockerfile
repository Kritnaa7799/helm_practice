# Use the official NGINX image from Docker Hub
FROM nginx:alpine

# Copy custom NGINX configuration file into the container
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80 for the web server
EXPOSE 80

# Start NGINX when the container runs
CMD ["nginx", "-g", "daemon off;"]
