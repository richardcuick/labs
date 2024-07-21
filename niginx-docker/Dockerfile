# Use a lightweight base image like Nginx
FROM nginx:alpine

# Copy your static website files to the appropriate directory in the container
COPY . /usr/share/nginx/html

# Expose port 80 for HTTP traffic
EXPOSE 80

# Start the Nginx server when the container starts
CMD ["nginx", "-g", "daemon off;"]