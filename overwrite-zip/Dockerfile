FROM phpearth/php:7.3-litespeed

COPY ./etc-litespeed-overwrite.zip /tmp
RUN apk add --no-cache zip \
 && unzip -o -d /etc/litespeed /tmp/etc-litespeed-overwrite.zip

EXPOSE 80
