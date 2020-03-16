# Image download
FROM ubuntu:latest 

RUN apt-get update && apt-get install -y haproxy

COPY ./files/haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg
