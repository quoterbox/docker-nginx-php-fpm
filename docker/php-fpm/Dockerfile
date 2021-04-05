FROM php:8.0.3-fpm-alpine3.13

RUN mv $PHP_INI_DIR/php.ini-development $PHP_INI_DIR/php.ini

COPY ../php/conf.d /usr/local/etc/php/conf.d
COPY ../php/php-fpm.d /usr/local/etc/php/conf.d

WORKDIR /app