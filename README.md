# CloudEngineLabs Assignment

## Overview

This repository contains the solution for the CloudEngine Labs DevOps & Cloud Engineer Assignment.

The project demonstrates:

* A simple Python application
* Docker containerization
* GitHub version control

## Project Structure

```
CloudEngineLabs_Assignment/
│── app.py
│── Dockerfile
└── README.md
```

## Python Program

The application prints the following message:

```
Hello, cloud-engine labs!!
```

Run locally:

```bash
python app.py
```

## Docker

### Build the Docker Image

```bash
docker build -t cloudenginelabs-app .
```

### Run the Docker Container

```bash
docker run --name cloudenginelabs-container cloudenginelabs-app
```

Expected Output:

```
Hello, cloud-engine labs!!
```

## Technologies Used

* Python 3.12
* Docker
* Git
* GitHub

## Author

**Arun C**

GitHub: https://github.com/Arun7272
## Last Updated