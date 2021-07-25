FROM centos:latest
LABEL maintainer="AmirContainer"
RUN yum -y install httpd
COPY index.html /var/www/html/
COPY Amir*.jpg /var/www/html/
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80

