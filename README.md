# 🚀 Flask + MySQL Docker Project

## 📌 Project Description
This project demonstrates a 2-tier application using:

- Flask (Python web framework)
- MySQL (Database)
- Docker (Containerization)
- Docker Compose (Multi-container setup)

---

## 🏗 Architecture

Flask Application → MySQL Database

Both run inside separate Docker containers and communicate using Docker network.

---

## Prerequisites

Before running this project, install:

- Docker
- Docker Compose

### Install Docker (Ubuntu)
$ sudo apt update
$ sudo apt install docker.io -y

### Start Docker
$ sudo systemctl start docker
$ sudo systemctl enable docker

### Check installation
$ docker --version
$ docker compose version



## ⚙️ How to Run This Project

### Step 1: Clone repository

$ git clone https://github.com/rutuja-tandel/flask-mysql-docker.git
$ cd flask-mysql-docker

### Step 2: Build Docker images

$ docker compose build
### Step 3: Start containers
docker compose up -d

### Step 4: Open application
http://<public-IP-of-your-instance>:5000

### 🎯 Expected Output
Flask Connected to MySQL Successfully!

### Stop containers
$ docker compose down
---
📌 Features
Dockerized Flask app
MySQL integration
Docker Compose orchestration
Service communication
DevOps project
---







