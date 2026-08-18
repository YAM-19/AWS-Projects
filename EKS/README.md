# Amazon EKS

## Overview

Amazon Elastic Kubernetes Service (EKS) is a managed Kubernetes service provided by AWS.

EKS allows us to run Kubernetes applications on AWS while AWS manages the Kubernetes control plane.

## Key Concepts

- **Control Plane** – Brain of Kubernetes, managed by AWS in EKS.
- **Pod** – Smallest deployable unit in Kubernetes.
- **Fargate** – Serverless compute option for running pods.
- **eksctl** – Command-line tool for creating and managing EKS clusters.
- **Ingress** – Manages incoming traffic to applications.
- **ALB** – Application Load Balancer used to route traffic.
- **OIDC** – OpenID Connect used for identity and IAM integration.
- **Helm** – Package manager for Kubernetes.

## Architecture

```text
Internet
   ↓
  ALB
   ↓
Ingress
   ↓
Service
   ↓
 Pod
   ↓
Fargate
   ↓
Application
