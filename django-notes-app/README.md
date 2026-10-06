# Django Notes App — Dockerized

An existing Django Notes application containerized and configured to run as a multi-container application using Docker Compose.

> The focus of this project is Dockerization and container deployment.

## Tech Stack

- Django
- Python
- MySQL
- Nginx
- Docker
- Docker Compose

## Architecture

```text
Client
  ↓
Nginx
  ↓
Django
  ↓
MySQL
```

## Docker Concepts

- Dockerfile
- Docker Compose
- Multi-container applications
- Nginx reverse proxy
- Container networking
- Persistent volumes
- Environment variables
- Healthchecks
- Restart policies

## Run Locally

### Prerequisites

- Git
- Docker

### 1. Clone

```bash
git clone https://github.com/aryan-aroraa/Docker-projects.git
cd Docker-projects/django-notes-app
```

### 2. Start

```bash
docker compose up --build
```

Or run in the background:

```bash
docker compose up --build -d
```

### 3. Open

```text
http://localhost
```

### 4. Stop

```bash
docker compose down
```
