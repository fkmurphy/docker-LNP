FROM php:7.3.5-fpm-alpine3.9

RUN apk add git \
	libzip-dev \
	zip \
	unzip 
RUN docker-php-ext-configure zip --with-libzip
RUN docker-php-ext-install pdo_mysql zip
RUN curl --silent --show-error https://getcomposer.org/installer | php && \
        mv composer.phar /usr/local/bin/composer
