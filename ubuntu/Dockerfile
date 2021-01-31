FROM ubuntu:18.04

RUN apt-get update

RUN apt-get install -y apache2 apache2-utils 

RUN apt-get clean

ENTRYPOINT /usr/sbin/apache2ctl -D FOREGROUND
