FROM php:8.1-apache

RUN apt-get update \
    && apt-get install -y libicu-dev \
    && docker-php-ext-install intl \
    && a2enmod rewrite

    