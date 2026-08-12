# Amazon EC2

## Overview

Amazon Elastic Compute Cloud (EC2) provides resizable virtual servers in the AWS Cloud.

## Key Concepts

### EC2 Instance

An EC2 instance is a virtual server that can be used to run applications and workloads.

### AMI

An Amazon Machine Image (AMI) is a template used to launch an EC2 instance. It contains the operating system and other required software.

### Instance Type

The instance type determines the compute resources available to an EC2 instance, such as CPU, memory, and networking capacity.

### Key Pair

A key pair is used to securely connect to an EC2 instance.

### Security Group

A security group acts as a virtual firewall that controls inbound and outbound traffic for an EC2 instance.

### Elastic IP

An Elastic IP address is a static public IPv4 address that can be associated with an EC2 instance.

### User Data

EC2 user data can be used to run commands automatically when an instance starts.

## EC2 Lifecycle

An EC2 instance can move through different states such as:

- Pending
- Running
- Stopping
- Stopped
- Terminating
- Terminated

## Key Takeaways

- EC2 provides virtual servers in AWS.
- AMIs are used to launch instances.
- Instance types determine compute resources.
- Security groups control network traffic.
- Key pairs help securely access instances.
- EC2 instances should be stopped or terminated when they are no longer needed to avoid unnecessary charges.
