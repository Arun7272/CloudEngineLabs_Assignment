# CloudEngineLabs Assignment

## Overview

This repository contains my solution for the CloudEngine Labs DevOps & Cloud Engineer Assignment.

The project demonstrates:

- Python application development
- Docker containerization
- Git version control
- GitHub repository management
- GitHub Actions (CI)
- Docker Hub image publishing
- Docker Compose

---

## Project Structure

```text
CloudEngineLabs_Assignment/
│── app.py
│── Dockerfile
│── docker-compose.yml
│── README.md
└── .github/
    └── workflows/
        └── docker-image.yml
```

---

## Python Program

The application prints:

```text
Hello, cloud-engine labs!!
```

Run locally:

```bash
python app.py
```

---

## Docker

### Build the Docker image

```bash
docker build -t cloudenginelabs-app .
```

### Run the Docker container

```bash
docker run --name cloudenginelabs-container cloudenginelabs-app
```

Expected Output:

```text
Hello, cloud-engine labs!!
```

---

## Docker Compose

Run the application using Docker Compose:

```bash
docker compose up
```

---

## GitHub Actions

A GitHub Actions workflow is configured to automatically build the Docker image whenever code is pushed to the **main** branch.

Workflow file:

```text
.github/workflows/docker-image.yml
```

---

## Docker Hub

Docker image:

```text
arun24082004/cloudenginelabs-app:latest
```

Pull the image:

```bash
docker pull arun24082004/cloudenginelabs-app:latest
```

---

## Technologies Used

- Python
- Docker
- Docker Compose
- Git
- GitHub
- GitHub Actions
- Docker Hub

---

## Author

**Arun C**

GitHub: https://github.com/Arun7272