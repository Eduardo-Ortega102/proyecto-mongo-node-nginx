# Web Server File 

FROM ubuntu

RUN apt update
RUN apt install -y nginx
RUN apt clean

COPY /src/ /var/www/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;" ]


