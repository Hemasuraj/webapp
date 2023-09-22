# Use an official Nginx runtime as a parent image
FROM nginx:alpine

# Copy your website content into the Nginx document root
COPY ./index.html /usr/share/nginx/html/

# Expose port 80 for the web server
EXPOSE 80

# Start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
