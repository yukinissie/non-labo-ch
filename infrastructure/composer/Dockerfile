FROM composer:1.10

WORKDIR /tmp

RUN composer --version \
    && composer config -g repositories.packagist composer https://packagist.jp \
    && composer global require hirak/prestissimo