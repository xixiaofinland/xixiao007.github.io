---
title: "Setup Docker Container Services in Personal Linux Server"
layout: post
tags: basic
comments: true
---

[Docker](https://www.docker.com/what-docker) is the main theme of this blog. It is the next generation cutting-edge hypervisor technology with many incredible powerful features. Among those features, **lightweight size**, **fast boot-up time**, and **isolation from host**, are key reasons for me to utilize docker in my personal Ubuntu server.

I will go through the setups for **4 docker containers** in five threads.

1. DynamicDNS using ddclient - *coming soon!*
2. OpenVPN Server - *coming soon!*
3. Nginx Reverse Proxy - *coming soon!*
4. Multiple Jekyll Blogs - *coming soon!*
5. Personal website - *coming soon!*

The final topology diagram is showed as below. We will eventually have:

- a OpenVPN server container to serve VPN services.
- a nginx reverse proxy container listening to port 80 and 443
- a Jekyll blog website behind nginx reverse proxy
- a personal website behind nginx reverse proxy


![my docker microservices](http://i.imgur.com/CnI8cyq.png?1 "my docker microservices")