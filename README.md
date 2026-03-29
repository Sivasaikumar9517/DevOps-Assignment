# DevOps Assignment

## Overview
This project demonstrates a minimal DevOps pipeline with:
- CI/CD using GitHub Actions
- Docker containerization
- Infrastructure provisioning using Terraform (AWS)

## Steps to Run

### Run App Locally
docker build -t devops-app .
docker run -p 3000:3000 devops-app

### Terraform Setup
cd terraform
terraform init
terraform apply

## CI/CD Pipeline
- Lint
- Test
- Build Docker Image
- Deploy Container

## Future Improvements
- Deploy to Kubernetes (EKS/GKE)
- Add monitoring (Prometheus, Grafana)
- Implement secure secrets management