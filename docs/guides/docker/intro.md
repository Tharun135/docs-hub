# Docker Intro

## Build & run
```bash
docker build -t myapp:latest .
docker run --rm -p 8080:80 myapp:latest
```

## Common
```bash
docker ps -a
docker images
docker logs <container>
docker exec -it <container> /bin/bash
```