# Devops-Projekt

Nginx running in Docker container.

## Stack
- Docker
- Nginx
- Alpine Linux

## Run locally
git clone https://github.com/Slavon777777777/devops-projekt.git
cd devops-projekt
**With Docker Compose (recommended):**
docker-compose up -d

**Without Docker Compose:**
docker build -t devops-projekt:v1 .
docker run --name projekt -d -p 8080:80 devops-projekt:v1

## Services
- **Nginx** - web server on port 8080
- **Whoami** - shows container info on port 8081

## Open in browser
http://localhost:8080
