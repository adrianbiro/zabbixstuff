[![Build images (DockerHub)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build.yml/badge.svg?branch=6.2&event=push)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build.yml)

## Original repo
[Github zabbix-docker](https://github.com/zabbix/zabbix-docker)

## Zabbix Dockerfiles

This repository contains **Dockerfile** of [Zabbix](https://zabbix.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/zabbix/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).

### Base Docker Image

* [ubuntu](https://hub.docker.com/_/ubuntu/)


### Usage

There is some documentation and examples in the [official Zabbix Documentation](https://www.zabbix.com/documentation/current/manual/installation/containers)!

Please also follow usage instructions of each Zabbix component image:

* [zabbix-appliance](https://hub.docker.com/r/zabbix/zabbix-appliance/) - Zabbix appliance with built-in MySQL server, Zabbix server, Zabbix Java Gateway and Zabbix frontend based on Nginx web-server
    > **Important information: Zabbix Docker Appliance has been decommissioned (except Red Hat edition) and will not be available for 3.0.31, 4.0.19, 4.4.7, 5.0.0 and newer releases. Please use a separate Docker images for each component instead of the all-in-one solution.**

* [zabbix-agent](https://hub.docker.com/r/zabbix/zabbix-agent/) - Zabbix agent
* [zabbix-agent2](https://hub.docker.com/r/zabbix/zabbix-agent2/) - Zabbix agent 2
* [zabbix-server-mysql](https://hub.docker.com/r/zabbix/zabbix-server-mysql/) - Zabbix server with MySQL database support
* [zabbix-server-pgsql](https://hub.docker.com/r/zabbix/zabbix-server-pgsql/) - Zabbix server with PostgreSQL database support
* [zabbix-web-apache-mysql](https://hub.docker.com/r/zabbix/zabbix-web-apache-mysql/) - Zabbix web interface on Apache2 web server with MySQL database support
* [zabbix-web-apache-pgsql](https://hub.docker.com/r/zabbix/zabbix-web-apache-pgsql/) - Zabbix web interface on Apache2 web server with PostgreSQL database support
* [zabbix-web-nginx-mysql](https://hub.docker.com/r/zabbix/zabbix-web-nginx-mysql/) - Zabbix web interface on Nginx web server with MySQL database support
* [zabbix-web-nginx-pgsql](https://hub.docker.com/r/zabbix/zabbix-web-nginx-pgsql/) - Zabbix web interface on Nginx web server with PostgreSQL database support
* [zabbix-proxy-sqlite3](https://hub.docker.com/r/zabbix/zabbix-proxy-sqlite3/) - Zabbix proxy with SQLite3 database support
* [zabbix-proxy-mysql](https://hub.docker.com/r/zabbix/zabbix-proxy-mysql/) - Zabbix proxy with MySQL database support
* [zabbix-java-gateway](https://hub.docker.com/r/zabbix/zabbix-java-gateway/) - Zabbix Java Gateway
* [zabbix-web-service](https://hub.docker.com/r/zabbix/zabbix-web-service/) - Zabbix web service for performing various tasks using headless web browser (for example, reporting)
* [zabbix-snmptraps](https://hub.docker.com/r/zabbix/zabbix-snmptraps/) - Additional container image for Zabbix server and Zabbix proxy to support SNMP traps

## Issues and Wiki

Be sure to check [the Wiki-page](https://github.com/zabbix/zabbix-docker/wiki) on common problems and questions. If you still have problems with or questions about the images, please contact us through a [GitHub issue](https://github.com/zabbix/zabbix-docker/issues).

