# Use the official NGINX image from Docker Hub.
# The 'alpine' tag refers to a lightweight version, which is great for production.
FROM nginx:1.25-alpine

# Copy the custom HTML file from your local machine to the NGINX web root directory inside the container.
COPY index.html /usr/share/nginx/html/index.html

COPY default.conf /etc/nginx/conf.d/default.conf

# Expose port 80 to allow traffic to the web server.
EXPOSE 80