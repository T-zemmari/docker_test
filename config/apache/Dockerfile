FROM php:7.1.33-apache
RUN docker-php-ext-install pdo pdo_mysql mysqli
RUN a2enmod rewrite
#RUN docker-php-ext-install gd
RUN docker-php-ext-install mbstring
RUN docker-php-ext-install opcache
#RUN docker-php-ext-install zip
#RUN service apache2 restart