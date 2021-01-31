FROM centos:latest

RUN yum update -y

RUN yum install -y httpd

ENTRYPOINT /usr/sbin/httpd -D FOREGROUND
