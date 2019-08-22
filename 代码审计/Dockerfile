FROM ctftraining/base_image_nginx_mysql_php_73

LABEL Author="galaxy"

COPY ./files /tmp/

RUN cp -rf /tmp/. /var/www/html \
    && ls /var/www/html  \
    && chown -R www-data:www-data /var/www/html