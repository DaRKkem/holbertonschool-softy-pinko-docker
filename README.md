# Softy Pinko Docker
![Docker](https://img.shields.io/badge/Docker-24.0-blue) ![Python](https://img.shields.io/badge/Python-3.12-blue) ![Flask](https://img.shields.io/badge/Flask-3.x-lightgrey) ![Nginx](https://img.shields.io/badge/Nginx-1.24-green)

This repository contains a progressive Docker project that incrementally builds a multi-service web architecture. Starting from a single container with a basic welcome script, it evolves through Flask API integration, multi-container orchestration, CORS configuration, Docker Compose management, reverse proxy setup, and horizontal scaling.

## Sub-Projects

| Task | Description |
|------|-------------|
| task0 | Docker basics -- FROM ubuntu, CMD echo "Hello, World!" |
| task1 | Python Flask API in Docker -- pip install, COPY, WORKDIR |
| task2 | Two-container architecture -- Nginx front-end + Flask back-end |
| task3 | CORS-enabled back-end -- flask-cors for cross-origin requests |
| task4 | Docker Compose orchestration -- services, ports, depends_on |
| task5 | Reverse proxy -- Nginx proxy routing / to front-end and /api to back-end |
| task6 | Horizontal scaling -- docker-compose up --scale back-end=2 |

---

Repository

GitHub repository: holbertonschool-softy-pinko-docker

---

Author

Damien Rossi - DaRKkem — Holberton School, cohort C28, Auvergne-Rhône-Alpes
