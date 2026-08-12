# VPC and Networking

## Overview

Amazon Virtual Private Cloud (VPC) allows you to create a logically isolated network for AWS resources.

## Key Concepts

### VPC

A VPC is a virtual network where AWS resources such as EC2 instances can run.

### Subnet

A subnet is a range of IP addresses within a VPC.

- Public subnet – can provide internet access through an Internet Gateway.
- Private subnet – does not have direct inbound internet access through an Internet Gateway.

### Internet Gateway

An Internet Gateway allows communication between resources in a VPC and the public internet when routing and security rules permit it.

### Route Table

A route table contains rules that determine where network traffic is directed.

### NAT Gateway

A NAT Gateway allows resources in a private subnet to make outbound connections to the internet without allowing unsolicited inbound internet connections.

### Security Group

A security group acts as a virtual firewall for resources such as EC2 instances and controls allowed inbound and outbound traffic.

### Network ACL

A Network ACL controls traffic at the subnet level and supports rules for inbound and outbound traffic.

## Basic VPC Architecture

Internet
↓
Internet Gateway
↓
Public Subnet
↓
EC2 Instance

A private subnet can use a NAT Gateway for outbound internet access.

## Key Takeaways

- VPC provides an isolated network in AWS.
- Subnets divide a VPC into smaller network segments.
- Route tables control traffic routing.
- Internet Gateways provide internet connectivity for public resources.
- NAT Gateways allow outbound internet access from private subnets.
- Security Groups protect individual resources.
- Network ACLs control traffic at the subnet level.
