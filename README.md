# Docker Projects

A collection of hands-on projects focused on learning and practicing Docker and containerization.

## Contents

- [Django Notes App](#1-django-notes-app)
- [Java Expense Tracker](#2-java-expense-tracker)
- [Flask App](#3-flask-app)
- [Node.js Todo App](#4-nodejs-todo-app)
- [Simple Java Docker](#5-simple-java-docker)
- [Docker Skills Practiced](#docker-skills-practiced)
- [Tools & Technologies](#tools--technologies)

## Projects

### 1. Django Notes App

Dockerized an existing Django Notes application and configured it to run as a multi-container application.

**Docker concepts practiced:**
- Dockerfile
- Docker Compose
- Multi-container applications
- Nginx reverse proxy
- MySQL containerization
- Docker networking
- Persistent volumes
- Healthchecks
- Restart policies
- Environment variables

**Architecture:**

    Client
       ↓
    Nginx
       ↓
    Django
       ↓
    MySQL


### 2. Java Expense Tracker

Dockerized an existing Spring Boot Expense Tracker application and configured it with Docker Compose.

**Docker concepts practiced:**
- Multi-stage Docker builds
- Maven
- Docker Compose
- MySQL containerization
- Docker networking
- Persistent volumes
- Healthchecks
- Restart policies
- Environment variables

**Architecture:**

    Spring Boot
         ↓
       MySQL


### 3. Flask App

A Flask application containerized with Docker and deployed on AWS EC2.

**Docker concepts practiced:**
- Dockerfile
- Docker image building
- Container execution
- Port mapping
- AWS EC2 deployment


### 4. Node.js Todo App

A Node.js Todo application containerized using a multi-stage Docker build.

**Docker concepts practiced:**
- Dockerfile
- Multi-stage builds
- Node.js dependencies
- Port mapping
- Docker images


### 5. Simple Java Docker

A basic Java application containerized with Docker.

**Docker concepts practiced:**
- Dockerfile
- Docker image building
- Container execution
- Port mapping


## Docker Skills Practiced

- Docker images & containers
- Dockerfiles
- Multi-stage builds
- Docker Compose
- Container networking
- Port mapping
- Volumes
- Environment variables
- Healthchecks
- Restart policies
- Nginx reverse proxy
- Docker Hub
- Docker Scout


## Tools & Technologies

- Docker
- Docker Compose
- Docker Hub
- Docker Scout
- Linux
- Git & GitHub
- AWS EC2
- Django
- Flask
- Node.js
- Java / Spring Boot
- MySQL
- Nginx
