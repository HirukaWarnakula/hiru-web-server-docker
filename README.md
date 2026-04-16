# Dockerized Nginx Web Server 🌐🐳

This project demonstrates how to host a static web page using **Nginx** inside a Docker container. It covers essential DevOps concepts like **Port Mapping** and **Docker Volumes**.

## 🛠️ Features
- **Nginx Integration:** High-performance web serving.
- **Docker Volumes:** Real-time updates without rebuilding the image.
- **Port Mapping:** Mapping container port 80 to host port 8080.

## 🚀 Deployment Instructions

### 1. Build the Image
```bash
docker build -t hiru-web-app .

```

2. Run with Live Sync (Volumes) 
 docker run -d -p 8080:80 --name hiru-server -v "$(pwd):/usr/share/nginx/html" nginx:latest

3. Access the Site

Open your browser and go to: http://localhost:8080

📸 Project Preview
(./web-preview.jpg)

Developed by Hiruka Warnakula – Final Year IT Undergraduate.