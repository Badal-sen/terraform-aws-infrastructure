# Terraform AWS Infrastructure Project

## Overview

This project demonstrates Infrastructure as Code (IaC) using Terraform on AWS. The infrastructure was provisioned entirely through Terraform configuration files instead of manually creating resources in the AWS Console.

The project deploys:

* AWS VPC
* Two Public Subnets
* Internet Gateway
* Route Table
* Security Group
* EC2 Web Server
* Apache HTTP Server
* Automated User Data Configuration

---

## Architecture

```text
Internet
    |
    v
Internet Gateway
    |
    v
VPC (10.0.0.0/16)
    |
    +----------------+
    |                |
    v                v
Public Subnet 1   Public Subnet 2
    |
    v
EC2 Instance
    |
    v
Apache Web Server
    |
    v
Web Application
```

---

## Technologies Used

* Terraform
* AWS EC2
* AWS VPC
* AWS Security Groups
* AWS Internet Gateway
* AWS Route Tables
* Apache HTTP Server
* Infrastructure as Code (IaC)

---

## Features

* Infrastructure deployed using Terraform
* Automated VPC creation
* Public subnet configuration
* Security group management
* EC2 instance provisioning
* Automatic Apache installation using User Data
* Automated web page deployment

---

## Terraform Files

| File         | Purpose                                      |
| ------------ | -------------------------------------------- |
| provider.tf  | AWS provider configuration                   |
| main.tf      | Infrastructure resources                     |
| variables.tf | Input variables                              |
| outputs.tf   | Output values                                |
| .gitignore   | Prevents sensitive files from being uploaded |

---

## Deployment Steps

### Initialize Terraform

```bash
terraform init
```

### Validate Configuration

```bash
terraform validate
```

### Review Execution Plan

```bash
terraform plan
```

### Deploy Infrastructure

```bash
terraform apply
```

### Destroy Infrastructure

```bash
terraform destroy
```

---

## Learning Outcomes

Through this project I learned:

* Terraform fundamentals
* Infrastructure as Code principles
* AWS networking concepts
* VPC and subnet design
* Security group configuration
* EC2 provisioning
* User Data automation
* Terraform state management

---

## Future Improvements

* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* CloudWatch Monitoring
* Prometheus & Grafana Integration
* Terraform Modules
* CI/CD Pipeline with GitHub Actions
* Kubernetes (EKS)

---

## Author

**Badal BK**

Aspiring Cloud & DevOps Engineer focused on AWS, Terraform, Kubernetes, Monitoring, and Infrastructure Automation.










 
