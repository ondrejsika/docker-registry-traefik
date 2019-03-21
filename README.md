# Docker Registry (for Traefik)

    2019 Ondrej Sika <ondrej@ondrejsika.com>

## Requirements

Traefik (with SSL)

- [Traefik with Let's Encrypt](https://github.com/ondrejsika/traefik-le)
- [Traefik with static certificate](https://github.com/ondrejsika/traefik-ssl)

## Install

```
git clone git@github.com:ondrejsika/docker-registry-traefik.git
cd docker-registry-traefik
HOSTNAME=registry.example.com docker-compose up -d
```