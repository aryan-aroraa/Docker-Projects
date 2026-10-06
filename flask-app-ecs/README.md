# Flask App — Dockerized

A Flask web application containerized with Docker and deployed on AWS EC2.

## Tech Stack

- Python
- Flask
- Docker
- AWS EC2

## Docker Concepts

- Dockerfile
- Docker image building
- Container execution
- Port mapping
- Multi-stage builds

## Run Locally

### Prerequisites

- Git
- Docker

### 1. Clone

```bash
git clone https://github.com/aryan-aroraa/Docker-projects.git
cd Docker-projects/flask-app-ecs
```

### 2. Build

```bash
docker build -t flask-app .
```

### 3. Run

```bash
docker run -d --name flask-app -p 80:80 flask-app
```

### 4. Open

```text
http://localhost
```

### 5. Stop

```bash
docker stop flask-app
docker rm flask-app
```
