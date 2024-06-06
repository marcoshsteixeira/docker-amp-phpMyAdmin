FROM phpmyadmin:latest

# Fix debconf warnings upon build
ARG DEBIAN_FRONTEND=noninteractive

COPY *.conf /etc/apache2/sites-available/

# Optmize docker
RUN apt-get clean \
    && apt-get autoclean \
    && apt-get autoremove

EXPOSE 8080