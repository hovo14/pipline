FROM ubuntu

RUN apt-get update

RUN apt-get install -y nginx  

RUN echo 'Hi, I am fucking your mommy' \

        >/usr/share/nginx/html/index.html

EXPOSE 80

CMD  [ "nginx", "-g", "daemon off"; ]
