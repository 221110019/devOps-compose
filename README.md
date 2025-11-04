# Setup & Run

- Harus Install Docker Desktop dan WSL2 (disarankan Ubuntu)
- Docker Desktop with WSL2 engine integration enabled pada setting
- Buka terminal Ubuntu
- (opsional) cd ke path folder

```bash
git clone https://github.com/221110019/devOps-compose.git
```

- cd ke folder clone
- Pull build image terbaru dari Docker Hub

```bash
docker compose pull
```

- Start

```bash
docker compose up
atau
docker compose up -d
atau
docker-compose up -d && docker-compose logs -f laravel.test-1`
```

- Akses web appp di http://localhost

- Stop

```bash
docker compose stop
```

- Stop and remove container

```bash
docker compose down
```

- Remove all container, volume, and image

```bash
docker container prune -f
docker volume prune -a -f
docker system prune -a -f
```
