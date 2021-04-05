FROM php:8.0.3-cli-alpine3.13

RUN mv $PHP_INI_DIR/php.ini-development $PHP_INI_DIR/php.ini

COPY ../php/___conf.d /usr/local/etc/php/conf.d

WORKDIR /app