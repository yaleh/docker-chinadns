docker-chinadns
==================

This Dockerfile builds an image with https://github.com/clowwindy/ChinaDNS.

Quick Start
-----------

    docker run -p 53:53/udp -d -t yaleh/docker-chinadns

Ports to map

* **53/udp**: DNS
