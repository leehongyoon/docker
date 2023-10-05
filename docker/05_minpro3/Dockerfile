FROM centos:7

RUN yum -y install httpd mod_wsgi && yum clean all

COPY vhost.conf /etc/httpd/conf.d
COPY myapp.wsgi /var/www/html/myapp.wsgi
