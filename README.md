# Docker-Kubernetes-DevOps

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Framework-lightgrey?style=for-the-badge&logo=flask)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue?style=for-the-badge&logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blue?style=for-the-badge&logo=kubernetes)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge&logo=mongodb)
![AWS EKS](https://img.shields.io/badge/AWS%20EKS-Managed%20Kubernetes-orange?style=for-the-badge&logo=amazonaws)

## Overview

This project demonstrates a straightforward frontend application built with **Python Flask**, containerized using **Docker**, and orchestrated with **Kubernetes**. The application utilizes **MongoDB** as its database and is deployed on a fault-tolerant cluster using **AWS EKS**. Docker images are stored in **DockerHub** for seamless deployment.

## Key Features

- **Python Flask Application**: Serves as the frontend of the application.
- **MongoDB Integration**: Provides database functionalities for the application.
- **Docker & Docker Compose**: Facilitates containerization and multi-container configurations.
- **Kubernetes Deployment**: Manages container orchestration with persistent storage and fault tolerance.
- **Persistent Volume Claim (PVC)**: Ensures **MongoDB** data persists even if the pod is restarted.
- **AWS EKS**: Hosts the Kubernetes cluster ensuring scalability and reliability.

## Architecture Diagram

```plaintext
User
  |
  v
Flask Application (Frontend)
  |
  v
MongoDB (Database) (Uses PVC for Persistent Storage)
```
## Future Enhancements

- **Implement User Authentication**: Enhance security by integrating user authentication mechanisms.
- **Add Unit and Integration Tests**: Ensure code reliability and maintainability.
- **Set Up Continuous Integration/Continuous Deployment (CI/CD)**: Automate testing and deployment pipelines.
