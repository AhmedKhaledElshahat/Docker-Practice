# 🧰 System Tool – Multi-Container Application using Docker Compose

This project demonstrates how to build a **multi-container application** using **Docker Compose**.  
It contains a **Frontend (Apache HTTPD)**, **Backend (Flask App)**, and **Database (MariaDB)** — connected through isolated Docker networks.

---

## 🚀 Project Overview

**System Tool** is a simple web application designed to help beginners understand how different containers communicate in a microservices-style setup.

It shows:
- How to connect containers with **Docker networks**.
- How to manage service dependencies.
- How to run a complete application stack using a single `docker compose up` command.

---

## 🧱 Components

| Service   | Technology | Description |
|------------|-------------|--------------|
| **Frontend** | Apache HTTPD | Serves a static HTML/CSS page showing your name and title. |
| **Backend** | Flask (Python) | Provides the app logic and communicates with the database. |
| **Database** | MariaDB | Stores data for the backend to use. |

---

## 🧩 Requirements

Before you begin, make sure you have these installed:

- 🐳 [Docker](https://docs.docker.com/get-docker/)
- ⚙️ [Docker Compose](https://docs.docker.com/compose/install/)

---

## ⚙️ Setup & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/AhmedKhaledElshahat/Docker-Practice.git
cd Docker-Practice
