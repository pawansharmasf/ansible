FROM centos
MAINTAINER pawan
RUN yum install httpd -y
RUN yum clean all
COPY index.html /var/www/html
COPY run.sh run.sh
CMD ./run.sh
