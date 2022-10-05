FROM vhphan/dienlanhphangia:latest
RUN docker-php-ext-install mysqli
COPY php.ini /usr/local/etc/php/php.ini
COPY 000-default.conf /etc/apache2/sites-available/000-default.conf