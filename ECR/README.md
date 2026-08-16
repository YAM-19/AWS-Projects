# Amazon ECR

## What is ECR?

ECR stands for Elastic Container Registry.

Amazon ECR is an AWS service used to store, manage, and distribute container images.

## Why is ECR used?

ECR provides a place to store Docker/container images so that AWS services can pull and run them.

## ECR vs Docker Hub

### Docker Hub
- Container registry provided by Docker
- Widely used for sharing and storing container images
- Large collection of public images

### Amazon ECR
- Container registry provided by AWS
- Integrates with AWS services such as ECS and EKS
- Works with AWS IAM for access control

## ECR Workflow

Dockerfile
↓
Docker Build
↓
Docker Image
↓
Tag Image
↓
Push Image to ECR
↓
ECS / EKS
↓
Container

## Important Concepts

- ECR Repository
- Docker Image
- Docker Build
- Docker Tag
- Docker Push
- Docker Pull
- ECR Authentication

## ECR Repository

A repository is a location in ECR where container images are stored.

Example:

ECR
↓
my-app
↓
v1
v2
v3
