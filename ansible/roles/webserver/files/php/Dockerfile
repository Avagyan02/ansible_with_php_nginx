FROM php:7.4-fpm

RUN docker-php-ext-install pdo pdo_mysql

WORKDIR /var/www/html

RUN chown -R www-data:www-data /var/www/html
