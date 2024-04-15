FROM debian:10

RUN apt update; apt upgrade -y  

RUN apt install nginx curl -y

COPY index.html /var/www/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
