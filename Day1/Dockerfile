FROM ubuntu:16.04
MAINTAINER Sunitha Udhayakumar

RUN apt-get update && apt-get install -y apache2
EXPOSE 8080
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]