FROM ubuntu:14.04
MAINTAINER Ronald Requena <rrequena@gmail.com>
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Hola, Prueba de contenedor' > /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]
EXPOSE 80
