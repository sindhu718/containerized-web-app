# Containerized Web App

This is a simple HTML/CSS/JavaScript web app containerized using Docker and Podman.

## 🛠️ Tools Used

- Docker
- Podman
- HTML, CSS, JavaScript

## 📦 How to Run

```bash
docker build -t my-web-app .
docker run -d -p 8080:80 my-web-app
