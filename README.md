# ProdManager - Fullstack Industrial Management System

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5-green)
![React](https://img.shields.io/badge/React-19-blue)
![Docker](https://img.shields.io/badge/Docker-ready-blue)

A comprehensive industrial production management system built to simulate real-world manufacturing workflows. This project features a robust Spring Boot API, a modern React frontend, and a containerized Oracle database.

## 🏗️ Project Architecture

This repository is organized as a **Monorepo**:

* **/prodmanager-api**: The backend engine (Java 17, Spring Boot, Spring Security, Flyway, Oracle DB).
* **/prodmanager-front**: The web interface (React 19, Vite, Axios, Nginx).
* **Root**: Orchestration layer using Docker Compose.

---

## 🚀 Quick Start (Recommended)

The entire environment is containerized. You don't need to install Java, Node, or Oracle locally.

### Prerequisites
* **Docker** and **Docker Compose** installed.

### Installation
1.  **Clone the repository:**
    ```bash
    git clone --recursive https://github.com/Vitor-C-Souza/prodmanager-challenge.git
    cd prodmanager-challenge
    ```

2.  **Start the services:**
    ```bash
    docker-compose up --build -d
    ```

3.  **Access the application:**
    * **Frontend:** [http://localhost](http://localhost)
    * **Backend API:** [http://localhost:8080/api/v1](http://localhost:8080/api/v1)
    * **Swagger Documentation:** [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

---

## ✨ Key Features Implemented

* 🔐 **Secure Authentication**: JWT-based login with role-based access control (ADMIN/USER).
* ⚙️ **Production Algorithm**: Intelligent prioritization logic based on profit margins (Higher revenue first).
* 📦 **Inventory Management**: Real-time stock tracking for products and raw materials.
* 📊 **Financial Reporting**: Automated simulation reports and revenue calculation.
* 🐳 **Production-Ready Infra**: Frontend served via optimized Nginx with Gzip and SPA routing.
* 🛡️ **CORS & Security**: Fully configured for cross-origin communication between containers.

---

## 🛠️ Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend** | Java 17, Spring Boot 3.x, Spring Security, JPA, Flyway |
| **Frontend** | React 19, TypeScript, Vite, Tailwind CSS |
| **Database** | Oracle Database XE 21c |
| **DevOps** | Docker, Docker Compose, Nginx |

---

## 👨‍💻 Author

**Vítor Cavalcante Souza**
* LinkedIn: [linkedin.com/in/vitorcavalcantesouza](https://www.linkedin.com/in/vitorcavalcantesouza)
* GitHub: [@Vitor-C-Souza](https://github.com/Vitor-C-Souza)

---
*Last updated: February 2026*