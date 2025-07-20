# EKS-K8S-Ingress-Project

This project demonstrates an end-to-end Kubernetes application deployment on **Amazon EKS**, using an **AWS ALB Ingress Controller** to expose the application via a public load balancer. 
The deployment includes configuring Kubernetes manifests, setting up an ingress resource, and verifying public access via the load balancer URL.


## Project Highlights

- Deployed a sample NGINX app on EKS using Kubernetes manifests
- Configured **Deployment**, **Service**, and **Ingress** resources
- Integrated **AWS ALB Ingress Controller** for traffic routing
- Verified deployment using `kubectl` commands and AWS Console
- Captured relevant **screenshots and verification steps**


## 🛠️ Tools & Technologies

- **Amazon EKS**
- **Kubernetes**
- **kubectl**
- **eksctl**
- **Helm**
- **ALB Ingress Controller**
- **AWS CLI**



## 📁 Project Structure

EKS-K8S-Ingress-Project/
├── manifests/
│ ├── deployment.yaml
│ ├── service.yaml
│ ├── ingress.yaml
├── alb-controller-setup.md
├── screenshots/
├── README.md
