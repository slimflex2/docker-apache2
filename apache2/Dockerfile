FROM ubuntu:xenial
LABEL maintainer="slimflex2@hotmail.com"
RUN apt-get update
RUN apt-get install iputils-ping -y
RUN apt-get install apache2 -y
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
