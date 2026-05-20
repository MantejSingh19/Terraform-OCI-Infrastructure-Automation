This repository contains the Terraform configurations and modules I worked on while learning and practicing OCI infrastructure automation. The main purpose of this project was to understand how real cloud infrastructure is provisioned and managed using Infrastructure as Code (IaC).

Instead of creating resources manually from the OCI Console, this project automates the complete setup using reusable Terraform modules.

The project includes networking components, compute provisioning, DRG attachments, LPG configuration, route tables, security lists, and subnet management inside Oracle Cloud Infrastructure (OCI).

What This Project Covers:
OCI VCN creation
Public and private subnet provisioning
Security Lists and Security Rules
Route Table creation and Route Rules
Compute Instance provisioning
Dynamic Routing Gateway (DRG)
DRG Attachments
Local Peering Gateway (LPG)
Reusable Terraform modules
Variable-driven infrastructure configuration

Modules Included:
modules/
│
├── VCN
├── Subnet
├── Route-Table
├── SL&SL-Rules
├── Compute
├── DRG
├── DRG-Attachment
└── LPG

Technologies Used:
Terraform
Oracle Cloud Infrastructure (OCI)
Linux
Git & GitHub

Project Structure:
.
├── main.tf
├── variables.tf
├── terraform.tfvars
├── provider.tf
│
├── modules/
│   ├── VCN/
│   ├── Subnet/
│   ├── Compute/
│   ├── Route-Table/
│   ├── SL&SL-Rules/
│   ├── DRG/
│   ├── DRG-Attachment/
│   └── LPG/

Key Learning Outcomes:
While working on this project, I got hands-on exposure to:

OCI networking concepts
Terraform module development
Infrastructure as Code (IaC)
Resource dependencies in Terraform
Dynamic resource provisioning using maps and variables
DRG and LPG networking concepts
Security rule management
Cloud infrastructure organization and modular design

Terraform Commands:
Initialize Terraform
terraform init
Validate Configuration
terraform validate
Preview Changes
terraform plan
Apply Infrastructure
terraform apply
