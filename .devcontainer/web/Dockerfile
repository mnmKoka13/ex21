FROM php:8.2-apache

RUN apt-get update -qq \
 && apt-get install -y --no-install-recommends \
    tzdata \
 && pecl install xdebug \
 && rm -rf /var/lib/apt/lists/*

ENV TZ="Asia/Tokyo"