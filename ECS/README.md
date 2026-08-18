# Amazon ECS

## Overview

Amazon Elastic Container Service (ECS) is a fully managed AWS service used to run and manage containerized applications.

## Key Concepts

- **Cluster** – Logical group of ECS resources.
- **Task Definition** – Blueprint that defines how a container should run.
- **Task** – Running instance of a task definition.
- **Service** – Maintains the desired number of running tasks.
- **Container** – Packages an application and its dependencies.
- **Fargate** – Serverless compute option for running containers.
- **EC2** – Allows containers to run on EC2 instances.

## Architecture

```text
ECS
 ↓
Cluster
 ↓
Service
 ↓
Task
 ↓
Container
 ↓
Application
