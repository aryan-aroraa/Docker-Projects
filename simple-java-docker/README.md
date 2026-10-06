# Simple Java App — Dockerized

A basic Java application containerized using Docker.

## Tech Stack

- Java
- Docker

## Docker Concepts

- Dockerfile
- Docker image building
- Container execution
- Port mapping

## Run Locally

### Prerequisites

- Git
- Docker

### 1. Clone

```bash
git clone https://github.com/aryan-aroraa/Docker-projects.git
cd Docker-projects/simple-java-docker
```

### 2. Build

```bash
docker build -t simple-java-app .
```

### 3. Run

```bash
docker run --name simple-java-app simple-java-app
```

### 4. Stop and Remove

```bash
docker rm simple-java-app
```
