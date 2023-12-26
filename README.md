Documentum 23.4 Docker environment (Docker/Alpine/Postgres/DA/REST/SSO?)
========================================================================

# Overview
- Documentum Server 23.4
- Postgres 15.5
- Docker Engine 24.0.7 

# Prerequisites
- OpenText support account (with access to download Documentum software) https://support.opentext.com/
- Fast enough computer (TBC)

# Notes
- Setup on a Windows 11 host
- Checked Documentum compatability using the _OpenText Documentum Infrastructure Certification Guide_

# Instructions
## Install Docker
1. Install Docker (Engine or Desktop)
2. https://docs.docker.com/get-docker/
3. Start Docker

## Setup Postgres
1. Within terminal run:
~~~
docker pull postgres:15.5
~~~
