# magento/Dockerfile
FROM php:7.4-apache

WORKDIR /var/www/html

COPY . .

RUN apt-get update && \
    apt-get install -y libfreetype6-dev libjpeg62-turbo-dev libpng-dev libxml2-dev && \
    docker-php-ext-install pdo_mysql gd soap

EXPOSE 80

CMD ["apache2-foreground"]
