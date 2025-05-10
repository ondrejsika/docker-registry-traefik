> [!TIP]
> <a href="https://ondrej-sika.cz/skoleni/docker"><img src="https://img.shields.io/badge/Školení%20Docker-by%20Ondřej%20Šika-0db7ed?style=for-the-badge&logo=docker&logoColor=white" style="width: 100%; height: auto;" alt="Školení Docker by Ondřej Šika" /></a>
>
> 🚀 Naučte se, jak efektivně pracovat s **Docker** kontejnery! Praktické školení vedené [Ondřejem Šikou](https://ondrej-sika.cz).
>
> 👉 [Více informací a registrace zde](https://ondrej-sika.cz/skoleni/docker)

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
