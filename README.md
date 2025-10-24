Multi-Cloud Auto-Deployment (Modified Project)

This project demonstrates multi-cloud deployment automation using Terraform and local Docker environments. It is a modified version of the original project, replacing AWS and GCP with local simulation, while retaining the core concepts of IaC, automation, and health checks.
Key Features

Automated provisioning of Docker containers as cloud nodes

Deployment of NGINX web servers

Health checks and routing simulation using DNSMasq

Single-command deployment using Terraform
Tools & Technologies

Terraform – Infrastructure as Code

Docker – Local container environments

NGINX – Web server deployment

DNSMasq / Local Host Configuration – Routing simulation

GitHub Codespaces / VS Code – Development environment
Initialize Terraform:
terraform init
Deploy the containers:
terraform apply
Project Notes

No AWS or GCP services used; local Docker containers simulate cloud nodes.

Maintains the core learning objectives of the original project: IaC, automation, deployment, and monitoring.
Conclusion

A cost-effective and practical implementation of multi-cloud deployment automation using Terraform and Docker, ideal for learning and experimentation.
