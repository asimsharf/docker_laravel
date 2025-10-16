FROM php:8.5.0RC2-fpm-alpine

COPY ./compose/workspace/run.sh /tmp

WORKDIR /var/www/html

ENTRYPOINT ["/tmp/run.sh"]