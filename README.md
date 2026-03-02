# 🐳 Dockerized WordPress & MySQL Architecture

## 📌 Project Overview
This repository contains my first complete Sysadmin/DevOps infrastructure as code (IaC) project. It demonstrates how to deploy a fully functional, multi-container web application using **Docker** and **Docker Compose**.

## 🏗️ Architecture
The system consists of two isolated containers communicating through a secure internal Docker network:
* **Frontend:** WordPress (Latest)
* **Database:** MySQL 5.7
* **Storage:** Persistent Docker Volumes for both database records and WordPress files to ensure data is not lost when containers are stopped.

## 🚀 How to Run
To spin up this entire infrastructure locally, you only need one command:

```bash
docker-compose up -d
