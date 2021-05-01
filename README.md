## minio-docker-letsencrypt-deploy
Distributed MinIO deployed via Docker Compose with autorenew ssl certificate using letsencrypt.

## Prerequisites

- [docker](https://docs.docker.com/get-docker/)
- [docker-compose](https://docs.docker.com/compose/install/)

## Quick Start

1. Create .env & edit it

```
cp .env.example .env
```

2. Start MinIO server

```
docker-compose down

docker-compose up -d
```

3. MinIO server' container health status

```
watch -n 3 "docker ps -a"
```

## License

This project is licensed under the GNU Affero General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
