###  EKS-K8S-Ingress-Project

This project demonstrates an end-to-end Kubernetes application deployment on **Amazon EKS**, using an **AWS ALB Ingress Controller** to expose the application via a public load balancer. 
The deployment includes configuring Kubernetes manifests, setting up an ingress resource, and verifying public access via the load balancer URL.


## Project Highlights

- Deployed a sample NGINX app on EKS using Kubernetes manifests
- Configured **Deployment**, **Service**, and **Ingress** resources
- Integrated **AWS ALB Ingress Controller** for traffic routing
- Verified deployment using `kubectl` commands and AWS Console
- Captured relevant **screenshots and verification steps**


## Tools & Technologies

- **Amazon EKS**
- **Kubernetes**
- **kubectl**
- **eksctl**
- **Helm**
- **ALB Ingress Controller**
- **AWS CLI**


## Screenshots

### 1. Deployment Verification
[SS1](screenshots/SS1.png)

### 2. ALB Created in AWS Console
[SS2](screenshots/SS2.png)

### 3. Service Created
[SS3](screenshots/SS3.png)

### 4. Ingress Deployed
[SS4](screenshots/SS4.png)

### 5. Load Balancer URL Opened in Browser
[SS5](screenshots/SS5.png)

### 6. Game Working in Browser
[SS6](screenshots/SS6.png)



## Project Structure

EKS-K8S-Ingress-Project/
├── manifests/
│ ├── deployment.yaml
│ ├── service.yaml
│ ├── ingress.yaml
├── alb-controller-setup.md
├── screenshots/
├── README.md
