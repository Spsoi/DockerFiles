FROM php:7.4-apache

RUN docker-php-ext-install \
    pdo_mysql \
    && a2enmod \
    rewrite \
    && echo "ServerName localhost" >> /etc/apache2/apache2.conf

# CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
