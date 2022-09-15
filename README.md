# Workspace for PostgreSQL with preconfigured PGAdmin

## Start containers

```
    docker compose up -d
```

## Stop containers and delete all volumes

```
    docker compose down -v
```

## PgAdmin

Go to http://localhost:8071

## PostgreSQL

- Host: localhost
- Dockerhost: host.docker.internal
- Port: 5438
- User: admin
- Password: pass