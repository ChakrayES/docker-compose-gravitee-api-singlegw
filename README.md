# docker-compose-gravitee-api-singlegw

## Description

Docker Compose environment with:

- Traefik Ingress
- Gravitee API Management 3.x

## DNS entries

Add the next entries to the /etc/hosts file (or DNS registry)

```
127.0.0.1   portainer.demo.chakray.internal api.demo.chakray.internal mgt-api.demo.chakray.internal mgt-ui.demo.chakray.internal portal-ui.demo.chakray.internal
```

## Startup

```
docker-compose up -d
```
