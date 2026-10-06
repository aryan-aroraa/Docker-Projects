# Node.js Todo App — Dockerized

A simple Node.js Todo application containerized using Docker.

## Tech Stack

- Node.js
- Express
- EJS
- Docker

## Docker Concepts

- Dockerfile
- Multi-stage builds
- Docker image building
- Port mapping
- Container execution

## Run Locally

### Prerequisites

- Git
- Docker

### 1. Clone

```bash
git clone https://github.com/aryan-aroraa/Docker-projects.git
cd Docker-projects/nodejs-todo
```

### 2. Build

```bash
docker build -t nodejs-todo .
```

### 3. Run

```bash
docker run -d --name nodejs-todo -p 3000:3000 nodejs-todo
```

### 4. Open

```text
http://localhost:3000
```

### 5. Stop

```bash
docker stop nodejs-todo
docker rm nodejs-todo
```
