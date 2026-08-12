# AWS Infrastructure Project

## Overview

This project demonstrates the design and deployment of a production-style AWS infrastructure using core AWS services. The architecture focuses on security, scalability, and high availability.

## Project Objectives

- Design a custom Amazon VPC
- Configure public and private subnets
- Launch Amazon EC2 instances
- Configure Security Groups
- Set up an Application Load Balancer (ALB)
- Implement an Auto Scaling Group

## AWS Services Used

- Amazon VPC
- Public Subnets
- Private Subnets
- Internet Gateway
- Route Tables
- Security Groups
- Amazon EC2
- Application Load Balancer (ALB)
- Target Group
- Auto Scaling Group

## Architecture

```text
Internet
    │
Internet Gateway
    │
Application Load Balancer
    │
Target Group
    │
Auto Scaling Group
    │
EC2 Instances
    │
Amazon VPC
```

## Implementation Steps

1. Created a custom Amazon VPC.
2. Configured public and private subnets.
3. Attached an Internet Gateway.
4. Created Route Tables and associated them with the subnets.
5. Configured Security Groups.
6. Launched EC2 instances.
7. Created a Target Group.
8. Configured an Application Load Balancer.
9. Created an Auto Scaling Group.
10. Configured and reviewed the AWS infrastructure components..

## Learning Outcomes

- AWS Networking
- VPC Design
- EC2 Deployment
- Load Balancing
- Auto Scaling
- High Availability
- Infrastructure Design

## Future Improvements

- Add architecture diagram
- Add project screenshots
- Configure CloudWatch monitoring
- Automate deployment using Terraform

## Author

**Yamini Arikatla**
