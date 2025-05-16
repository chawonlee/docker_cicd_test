FROM php:7.4-apache

# PHP 확장 설치 (선택사항: MySQL 연동 등)
RUN docker-php-ext-install mysqli pdo pdo_mysql

# 아파치 DocumentRoot 설정
RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf

# UTF-8 문제 해결을 위한 설정 (선택)
ENV LANG C.UTF-8