# Reverse Proxy

Configuración de NGINX como reverse proxy para entornos Docker.

## Tecnologías

- NGINX
- Docker
- Docker Compose

## Funcionalidades

- Reverse Proxy HTTP
- Balanceo de carga
- Integración con redes Docker
- Configuración centralizada mediante NGINX

## Arquitectura

```text
Internet
    │
    ▼
NGINX
 ├── Portafolio
 └── NetServices
```

## Ejecución

```bash
docker compose up -d --build
```

## Estado

✅ Configuración reutilizable para despliegues locales y plataformas cloud como Oracle Cloud Infrastructure (OCI), AWS, Microsoft Azure.

## Autor

Dagoberto Duran

Cloud Engineer | System Administrator | DevOps
