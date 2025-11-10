# 🚀 AWS EKS Terraform CI/CD

End-to-end DevOps pipeline using **Docker**, **Terraform**, and **GitHub Actions** to build, push, and deploy containerized apps on **AWS EKS**.

## ⚙️ Workflow
1. **Build** Docker images for backend, frontend, and MongoDB  
2. **Push** images to AWS **ECR**  
3. **Provision** EKS cluster using **Terraform**  
4. **Deploy** workloads via Kubernetes manifests  

## 🧩 Tech Stack
Docker • Terraform • AWS ECR • EKS • GitHub Actions • Node.js • MongoDB

## 📁 Structure
.github/workflows/ # CI/CD pipeline
backend/ # Node.js app
frontend/ # React app
mongo/ # MongoDB container setup
terraform/ # EKS infrastructure code
k8s/ # Deployment manifests


## 🔑 GitHub Secrets
`AWS_ACCESS_KEY_ID` • `AWS_SECRET_ACCESS_KEY` • `AWS_REGION` • `ECR_REPOSITORY`

## 👨‍💻 Author
**Mohammad Abis** — Linux & Cloud Administrator  
AWS | Terraform | Docker | Kubernetes
