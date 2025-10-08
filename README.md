# 🐳 Docker & ☸️ Kubernetes Learning Application

This project is a hands-on **learning application** built to explore and practice **containerization** using **Docker** and **container orchestration** using **Kubernetes**.  

It covers the full workflow — from creating a simple application, containerizing it, to deploying and managing it in a Kubernetes cluster.

---

## 📚 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
  - [Prerequisites](#-prerequisites)
  - [Installation](#-installation)
- [Docker Setup](#-docker-setup)
- [Kubernetes Deployment](#-kubernetes-deployment)
- [Project Structure](#-project-structure)
- [Learning Outcomes](#-learning-outcomes)
- [Useful Commands](#-useful-commands)
- [License](#-license)

---

## 🧾 About the Project

This repository contains a simple application used as a **learning playground** to understand:

- How to build and containerize applications with **Docker**.
- How to push and pull images from Docker Hub.
- How to deploy and scale applications using **Kubernetes**.
- How to work with Pods, Services, Deployments, and ConfigMaps.

The application demonstrates a basic end-to-end deployment workflow, making it easy for beginners to follow.

---

## ✨ Features

- 🐳 Dockerized application (Dockerfile + .dockerignore)  
- ☸️ Kubernetes manifests for deployment and service  
- 🚀 Easy to spin up locally on Minikube  
- 🧰 Clean and well-structured code for learning

---

## 🧰 Tech Stack

- **Backend**: Node.j
- **Containerization**: Docker
- **Orchestration**: Kubernetes (Minikube)
- **Registry**: Docker Hub (or any container registry)

---

## 🚀 Getting Started

### ✅ Prerequisites

Before running the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (if applicable)
- [Docker](https://www.docker.com/)
- [Kubernetes](https://kubernetes.io/) (Minikube or kind recommended)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [Docker Hub account](https://hub.docker.com/) (optional)

### 🛠 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/docker-kubernetes-learning.git

# Navigate to the project directory
cd docker-kubernetes-learning

# Install dependencies
npm install
