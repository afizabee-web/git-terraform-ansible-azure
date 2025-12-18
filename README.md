# Git + Terraform + Ansible (Azure)

## Project Overview
This project demonstrates Infrastructure and Configuration automation using:
- Terraform (Azure infrastructure provisioning)
- Ansible (Linux server configuration)
- Git (version control)

## Architecture
- Terraform provisions an Azure Linux VM and networking resources
- Ansible installs and configures NGINX on the VM

## Tools Used
- Azure
- Terraform
- Ansible
- Git
- SSH (key-based authentication)

## How to Run

### 1. Provision Infrastructure
```bash
cd terraform
terraform init
terraform apply
