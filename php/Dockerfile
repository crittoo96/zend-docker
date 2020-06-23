FROM php:7.3-apache
# COPY ./php.ini /usr/local/etc/php/
# COPY ./*.conf /etc/apache2/sites-enabled/
# COPY ./.htaccess /var/www/html/demos/Zend/Cloud/cloudexp/public/

RUN apt-get update
RUN apt-get install -y vim default-mysql-client
RUN docker-php-ext-install pdo_mysql

RUN a2enmod rewrite
# RUN apt-get update
# RUN apt-get install -y vim default-mysql-client
# RUN docker-php-ext-install pdo_mysql