FROM ubuntu:18.04
MAINTAINER Ivan Dmytrenko
RUN apt-get update
RUN apt-get -y install nginx
RUN apt-get clean all
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
COPY index.html /var/www/html/
CMD [ "nginx" ]
