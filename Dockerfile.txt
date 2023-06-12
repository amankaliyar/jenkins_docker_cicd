# Use a base image
FROM nginx:alpine

# Copy the HTML file to the web server's document root
COPY index.html /usr/share/nginx/html/

# Expose port 80 to allow incoming web traffic
EXPOSE 80
