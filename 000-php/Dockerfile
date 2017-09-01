FROM php:7.1-fpm

RUN pecl install xdebug-2.5.3 \
    && docker-php-ext-enable xdebug

COPY xdebug.ini /usr/local/etc/php/conf.d/docker-php-ext-xdebug.ini