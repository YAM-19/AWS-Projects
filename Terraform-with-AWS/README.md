# Terraform with AWS

## Overview

Terraform is an Infrastructure as Code (IaC) tool developed by HashiCorp.

It allows infrastructure to be created, managed, and modified using code instead of manually configuring resources through the AWS Console.

## Why Terraform?

- Infrastructure as Code
- Automation
- Repeatable infrastructure
- Version control
- Faster deployments
- Consistent infrastructure management

## Terraform Workflow

Write Terraform Code
        ↓
terraform init
        ↓
terraform plan
        ↓
terraform apply
        ↓
AWS Infrastructure

## Important Commands

### terraform init

Initializes the Terraform working directory and downloads the required providers.

### terraform plan

Shows the changes Terraform will make to the infrastructure.

### terraform apply

Creates or updates the infrastructure based on the Terraform configuration.

### terraform destroy

Removes the infrastructure managed by Terraform.

## Terraform with AWS

Terraform can be used to manage AWS resources such as:

- VPC
- Subnets
- EC2
- Security Groups
- S3
- IAM
- Load Balancers

## Terraform Provider

The AWS provider allows Terraform to communicate with AWS and manage AWS resources.

## Cost

Terraform itself is free and open-source.

AWS resources managed through Terraform may incur charges depending on the resources and usage.

## Key Takeaways

- Terraform is an Infrastructure as Code tool.
- Terraform uses configuration files to manage infrastructure.
- `terraform init` → Initialize
- `terraform plan` → Preview changes
- `terraform apply` → Create or update resources
- `terraform destroy` → Remove resources
- Terraform is widely used in DevOps and cloud environments.
