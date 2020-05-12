FROM ubuntu:latest

RUN apt update
RUN apt install -y nginx
RUN echo 'nginx' > /var/www/html/index.html

ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
EXPOSE 80

