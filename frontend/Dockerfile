# Use an official Nginx image as a parent image
FROM nginx:latest

# Copy your Nginx configuration file to the container
COPY nginx.conf /etc/nginx/nginx.conf

# Copy your frontend files to the Nginx web root directory
COPY ./ /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
