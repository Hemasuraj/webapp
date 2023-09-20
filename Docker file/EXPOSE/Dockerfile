FROM ubuntu

LABEL AUTHOR=suraj

RUN apt update

RUN apt install nginx -y

CMD ["nginx","-g","daemon","off",]

EXPOSE 8080
