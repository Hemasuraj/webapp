# Use an official Nginx runtime as a parent image
FROM nginx:alpine

#Update the apt repository
RUN apk update 

#Install nginx 
RUN apk add nginx 

#Removing existing index.html file 
RUN rm -f /usr/share/nginx/html/index.html

# Copy your website content into the Nginx document root
COPY ./index.html /usr/share/nginx/html/

# Expose port 80 for the web server
EXPOSE 80

# Start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
