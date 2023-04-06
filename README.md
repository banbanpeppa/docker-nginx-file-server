# Nginx File Server Based on Docker Compose

A Nginx file server based on docker compose, enjoy.

## Usage

```bash
git clone https://github.com/banbanpeppa/nginx-file-server.git
```

generate password file
```
docker run --rm -it jess/htpasswd -nb nginx nginxpw > nginx.passwd
```

start server

```bash
docker-compose up -d
```

Just put the file to the path `${PWD}/file_store`

## Config

Change the port of server by modifying `.env`.
