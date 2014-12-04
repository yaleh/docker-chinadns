docker-shadowsocks
==================

This Dockerfile builds an image with https://github.com/clowwindy/ChinaDNS.

Quick Start
-----------

    docker run -p 53:53/udp -d -i yaleh/docker-chinadns

Ports to map

* **53/udp**: DNS
