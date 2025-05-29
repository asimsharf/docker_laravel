FROM php:8.4.8RC1-fpm-alpine

COPY ./compose/workspace/run.sh /tmp

WORKDIR /var/www/html

ENTRYPOINT ["/tmp/run.sh"]