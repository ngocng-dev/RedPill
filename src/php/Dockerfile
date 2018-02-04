FROM php:5-apache
RUN apt-get update && apt-get install -y php5.6-mysql
RUN docker-php-ext-install -j$(nproc) mysql
