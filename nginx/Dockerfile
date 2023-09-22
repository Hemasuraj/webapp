# Use an official Nginx runtime as a parent image
FROM nginx:alpine

#Update the apt repository
RUN yum update -y

#Install nginx 
RUN apt install nginx -y

# Copy your website content into the Nginx document root
COPY ./index.html /usr/share/nginx/html/

# Expose port 80 for the web server
EXPOSE 80

# Start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
