# alpine-yarn-nginx
Docker image that ships Node, Npm, and Nginx together.

Latest version:

Item | Version
------- | -----
Node | v10.14.2
Npm | v6.4.1
Yarn | v1.12.3
Nginx | v1.15.7

## Supported tags
* `10.14.2`, `latest` [(Dockerfile)](./Dockerfile)
* `8.12.0` [(Dockerfile)](https://github.com/ExiaSR/alpine-yarn-nginx/blob/8.12.0/Dockerfile)
* `8.9.4` [(Dockerfile)](https://github.com/ExiaSR/alpine-yarn-nginx/blob/8.9.4/Dockerfile)
* `7.9.4` [(Dockerfile)](https://github.com/ExiaSR/alpine-yarn-nginx/blob/7.9.4/Dockerfile)

## Usage

`$ docker pull exiasr/alpine-yarn-nginx`

Static files are served under `/usr/share/nginx/html` by default, or you may modify the config file for reverse proxy.
