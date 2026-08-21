# Docker-Task3
# Custom Nginx Docker Deployment Using Docker Compose

## Project Overview

This project demonstrates how to create a custom Nginx Docker image and deploy it using Docker Compose on an AWS EC2 instance.

The Nginx container uses a bind mount from the EC2 host:

/var/opt/nginx → /usr/share/nginx/html

The custom Docker image is also pushed to Docker Hub, and the complete project files and output screenshots are maintained in GitHub.

---

## Technologies Used

- AWS EC2
- Ubuntu
- Docker
- Docker Compose
- Nginx
- Docker Hub
- Git
- GitHub

---

## Project Objective

The main objectives of this task are:

1. Create a custom Nginx Docker image.
2. Deploy the custom image using Docker Compose.
3. Configure a bind mount at `/var/opt/nginx`.
4. Run Nginx on an AWS EC2 instance.
5. Verify the application through the EC2 public IP.
6. Push the custom Docker image to Docker Hub.
7. Push project files and screenshots to GitHub.

---

## Project Structure

```text
custom-nginx/
│
├── Dockerfile
├── docker-compose.yml
├── nginx.conf
├── README.md
│
├── html/
│   └── index.html
│
└── screenshots/
    ├── ec2.png
    ├── docker-image.png
    ├── docker-compose.png
    ├── bind-mount.png
    └── nginx-output.png
