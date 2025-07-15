# 🐳 Docker CLI Essentials

Commands to help manage containers, images, and volumes using Docker.

## 🧭 Basic Usage

```bash
docker ps -a
docker images
```

## 🏃 Run & Exec

```bash
docker run -it ubuntu bash
docker exec -it <container_id> bash
```

## 📦 Build & Tag

```bash
docker build -t my-image .
docker tag my-image myrepo/my-image:v1
```

## 📤 Push & Pull

```bash
docker push myrepo/my-image
docker pull ubuntu:latest
```

## 🧼 Clean Up

```bash
docker rm $(docker ps -aq)
docker rmi $(docker images -q)
docker system prune
```