FROM centos:7

MAINTAINER saikrishna.ura@gmail.com

RUN yum update -y

RUN yum -y install httpd

COPY . /var/www/html/

CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]

EXPOSE 80
