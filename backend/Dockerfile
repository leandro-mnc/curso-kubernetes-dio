FROM php:8.1-apache

WORKDIR /var/www/html/

COPY *.php /var/www/html/

RUN docker-php-ext-install mysqli

EXPOSE 80