FROM php:7.2-apache
RUN apt-get update && \
  docker-php-ext-install pdo_mysql mysqli mbstring

RUN apt-get -y install zip unzip

RUN a2enmod rewrite \
  && service apache2 restart