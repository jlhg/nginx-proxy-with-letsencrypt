# Nginx Proxy with Let's Encrypt

This docker compose file is created based on
[jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy) and
[JrCs/docker-letsencrypt-nginx-proxy-companion](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion).

## Getting Started

Run `docker-compose up -d` at the current directory to start containers.

Start any service container with the following environment variables:

```
VIRTUAL_HOST=www.example.com
LETSENCRYPT_HOST=www.example.com
LETSENCRYPT_EMAIL=foobar@example.com
```
