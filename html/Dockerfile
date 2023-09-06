FROM centos:centos7
LABEL name Ramana
RUN yum install httpd -y
EXPOSE 80
COPY . /var/www/html
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]

