FROM nginx:alpine

LABEL AUTHOR=surajkumar

WORKDIR usr/share/nginx/html

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 8082:80

CMD [ "nginx" , "-g" , "daemon" ,"off", ]

