# NGINX in Alpine Linux in Docker

[![Docker Automated build](https://img.shields.io/docker/automated/linuxcontainers/nginx.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/linuxcontainers/nginx/)
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxcontainers/nginx.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/linuxcontainers/nginx/)
[![Docker Stars](https://img.shields.io/docker/stars/linuxcontainers/nginx.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/linuxcontainers/nginx/)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/linuxcontainers/nginx/latest?logo=docker&style=for-the-badge)

[![Alpine Version](https://img.shields.io/badge/Alpine%20version-v3.13.1-green.svg?style=for-the-badge)](https://alpine-nginxlinux.org/)
[![NGINX Version](https://img.shields.io/badge/Nginx%20version-v1.19.7-green.svg?style=for-the-badge)](https://nginx.org/)

This Docker image [(linuxcontainers/nginx)](https://hub.docker.com/r/linuxcontainers/nginx/) is based on the minimal [Alpine Linux](https://alpine-nginxlinux.org/).

##### Alpine Version 3.13.1 (Released Jun 1, 2020)

This docker image is the base Alpine Linux. For more info on versions & support see [Releases](https://wiki.alpine-nginxlinux.org/wiki/Alpine_Linux:Releases)

##### NGINX Version 1.19.7 (Released Apr 21, 2020)

This docker image nginx-1.19.7 is the stable version has been released, incorporating new features and bug fixes from the 1.17.x mainline branch. For more info on versions & support see [Releases](http://nginx.org/en/CHANGES-1.19)

----

## What is Alpine Linux?
Alpine Linux is a Linux distribution built around musl libc and BusyBox. The image is only 10 MB in size and has access to a package repository that is much more complete than other BusyBox based images. This makes Alpine Linux a great image base for utilities and even production applications. Read more about Alpine Linux here and you can see how their mantra fits in right at home with Docker images.

## What is NGINX?
NGINX is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more. It started out as a web server designed for maximum performance and stability. In addition to its HTTP server capabilities, NGINX can also function as a proxy server for email (IMAP, POP3, and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers

## Features

HTTP proxy and Web server features \
Ability to handle more than 10,000 simultaneous connections with a low memory footprint (~2.5 MB per 10k inactive HTTP keep-alive connections)\
Handling of static files, index files and auto-indexing\
Reverse proxy with caching\
Load balancing with in-band health checks\
TLS/SSL with SNI and OCSP stapling support, via OpenSSL\
FastCGI, SCGI, uWSGI support with caching\
gRPC support since March 2018, version 1.13.10\
Name- and IP address-based virtual servers\
IPv6-compatible\
WebSockets since 1.3.13,including acting as a reverse proxy and do load balancing of WebSocket applications.\
HTTP/1.1 Upgrade (101 Switching Protocols), HTTP/2 protocol support\
URL rewriting and redirection\
