# 🐳 NGINX on Minikube — Kubernetes Lab

This is a basic deployment of an NGINX web server on a local Minikube Kubernetes cluster using Docker Desktop as the container runtime.

## ✅ Prerequisites

- macOS with Apple Silicon (M1/M2)
- Docker Desktop installed and running
- Minikube installed (`brew install minikube`)
- kubectl installed (`brew install kubectl`)
- VS code

---

## 🚀 Steps

### 1. Start Minikube

```bash
minikube start --driver=docker
