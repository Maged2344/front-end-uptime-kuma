![image](https://github.com/user-attachments/assets/8408e059-6b1e-4e3d-81d9-31f136e05c7a)

# Uptime Kuma Docker Deployment

This repository contains a **GitHub Actions workflow** that automates the deployment of the `uptime-kuma` Docker container. The workflow builds and deploys the container to a server, ensuring it is always up-to-date and running smoothly.

## 🚀 Project Overview

**Uptime Kuma** is a self-hosted status monitoring solution that can be used to monitor the uptime of your services. This project includes a GitHub Actions workflow that:
- **Stops** any running `uptime-kuma` containers.
- **Removes** the old container.
- **Runs** a new container with the latest `uptime-kuma` image, using Docker.

The workflow uses Docker to manage the container lifecycle and ensures that the `uptime-kuma` service is always running and available on port `3001`.

## 🛠️ Prerequisites

Before running the workflow, ensure that you have the following set up:

- **Docker**: Docker should be installed and running on your server.
- **GitHub Repository**: This workflow is triggered by commits to the repository. You can use this with any repository that requires Docker deployment.
- **GitHub Actions**: This workflow utilizes GitHub Actions for CI/CD automation.
- ![image](https://github.com/user-attachments/assets/1bc0c2e1-c9a1-4b2a-aa42-a1aca41a4f1c)

