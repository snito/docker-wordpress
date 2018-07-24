FROM php:5.6-apache

COPY index.php .
COPY php.ini /usr/local/etc/php/

RUN a2enmod rewrite

RUN apt-get update && \
  docker-php-ext-install mysql mysqli pdo pdo_mysql mbstring