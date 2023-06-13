# FROM komljen/ubuntu
FROM golang:1.19
MAINTAINER Alen Komljen <alen.komljen@live.com>

RUN \
  apt-get update && \
  apt-get -y install \
          apache2 && \
  rm /var/www/html/index.html && \
  rm -rf /var/lib/apt/lists/*
  
RUN curl -vLO https://github.com/int128/kubelogin/releases/download/v1.27.0/kubelogin_linux_amd64.zip
