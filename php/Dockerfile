FROM debian:jessie

MAINTAINER Peter

RUN apt-get update && apt-get -y install \
php5-cgi \
php5-gd \
apt-get clean autoclean && apt-get autoremove && \
rm -rf /var/lib/{apt,dpkg,cache,log}

RUN docker-php-ext-configure gd --with-freetype-dir=/usr/include/ --with-jpeg-dir=/usr/include/ && docker-php-ext-install gd
 

