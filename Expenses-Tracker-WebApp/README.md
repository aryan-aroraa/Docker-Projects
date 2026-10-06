# Java Expense Tracker — Dockerized

A Spring Boot Expense Tracker application containerized and configured to run with Docker Compose.

> The focus of this project is Dockerization and container deployment.

## Tech Stack

- Java / Spring Boot
- Maven
- MySQL
- Docker
- Docker Compose

## Architecture

```text
Spring Boot → MySQL
```

## Docker Concepts

- Multi-stage Docker builds
- Docker Compose
- Container networking
- Environment variables
- Persistent volumes
- Healthchecks
- Restart policies

## Run Locally

### Prerequisites

- Git
- Docker

### 1. Clone

```bash
git clone https://github.com/aryan-aroraa/Docker-projects.git
cd Docker-projects/Expenses-Tracker-WebApp
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
http://localhost:8080
```

### 4. Stop

```bash
docker compose down
```
