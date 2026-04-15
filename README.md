# 🚀 Production DevOps Project (AWS + Kubernetes + CI/CD)

## 📌 Overview
This project demonstrates a full production-style DevOps pipeline deployed on AWS using modern tools.

## 🧱 Tech Stack
- AWS EC2 (Infrastructure)
- Terraform (Infrastructure as Code)
- Docker (Containerization)
- Kubernetes (K3s)
- NGINX Ingress Controller
- GitHub Actions (CI/CD)
- Let's Encrypt (HTTPS SSL)
- Linux & Nginx

## ⚙️ Features
- Automated infrastructure provisioning using Terraform
- Containerized application deployment with Docker
- Kubernetes orchestration using K3s
- CI/CD pipeline for automated deployment
- Custom domain routing using Ingress
- Secure HTTPS with SSL certificates

## 🌐 Live Application
👉 https://jomards.com

## 📂 Project Structure
- terraform/ → Infrastructure setup
- k8s/ → Kubernetes manifests
- .github/workflows/ → CI/CD pipeline

## 🚀 Author
Idris Olakojo

## 📸 Architecture Diagram

User → Domain (jomards.com) → NGINX Ingress → Kubernetes Service → Docker Container

## 🔄 CI/CD Workflow

1. Developer pushes code to GitHub
2. GitHub Actions builds Docker image
3. Image is deployed to Kubernetes cluster
4. Application updates automatically

## 📊 Key Achievements

- Built a full production-ready DevOps pipeline from scratch
- Automated infrastructure provisioning using Terraform
- Implemented Kubernetes-based deployment using K3s
- Secured application with HTTPS (SSL)
- Configured domain routing using Ingress

## 🧠 What I Learned

- Kubernetes networking (Ingress, Services)
- Infrastructure as Code (Terraform)
- CI/CD pipeline automation
- Cloud deployment best practices
