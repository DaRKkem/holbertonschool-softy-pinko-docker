# Softy Pinko Docker

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

**Author:** Damien Rossi - **[DaRKkem](https://github.com/DaRKkem)** -- Holberton School, cohort C28, Auvergne-Rhone-Alpes
