# Devops-Projekt

Nginx running in Docker container.

## Stack
- Docker
- Nginx
- Alpine Linux

## Run locally
git clone https://github.com/Slavon777777777/devops-projekt.git
cd devops-projekt
docker build -t devops-projekt:v1 .
docker run --name projekt -d -p 8080:80 devops-projekt:v1

## Open in browser
http://localhost:8080
