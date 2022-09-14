# Nginx File Server Based on Docker Compose

A Nginx file server based on docker compose, enjoy.

## Usage

```bash
git clone https://github.com/banbanpeppa/nginx-file-server.git
```

start server

```bash
cd nginx-file-server
docker-compose up -d
```

Just put the file to the path `${PWD}/file_store`

## Config

Change the port of server by modifying `.env`.
