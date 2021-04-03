FROM ubuntu:18.04
RUN apt-get update
RUN apt-get -y install sudo
RUN apt-get -y install apache2
CMD ["apache2ctl", "-D","FOREGROUND"]