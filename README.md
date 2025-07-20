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

### SS1.png  
**2048 Game - Browser Launch**  
Game is successfully loaded via the ALB DNS.
[2048 Game Home](screenshots/SS1.png)
[2048 Game Footer](screenshots/SS2.png)

### SS3.png  
**AWS Console - ALB State**  
Shows ALB in "Active" state with correct VPC.
[ALB Active in AWS](screenshots/SS3.png)


### SS4.png  
**Kubernetes - ALB Controller Running**  
ALB Controller is deployed and ready.
[ALB Controller Deployment](screenshots/SS4.png)


### SS5.png  
**Kubernetes - 2048 Pods Running**  
All pods are up and running.
[Pods Running](screenshots/SS5.png)


### SS6.png  
**Kubernetes - Service & Deployment Status**  
Shows NodePort service and replicas for the 2048 app.
[Service and Deployment Info](screenshots/SS6.png)
