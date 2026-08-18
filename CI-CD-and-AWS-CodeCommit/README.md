# CI/CD and AWS DevOps Services

## Overview

This project covers the concepts of Continuous Integration (CI), Continuous Delivery/Deployment (CD), Jenkins, and AWS CI/CD services.

## CI/CD

CI/CD automates the process of integrating, building, testing, and deploying application code.

### CI/CD Flow

Developer → Source Repository → Build → Test → Deploy → Application

## AWS CI/CD Services

### AWS CodeCommit

AWS CodeCommit is a managed source control service used to store and manage source code repositories.

### AWS CodeBuild

AWS CodeBuild is a fully managed build service used to compile code, run tests, and create build artifacts.

**CodeBuild → Build and Test**

### AWS CodeDeploy

AWS CodeDeploy is a deployment service used to automate application deployments.

**CodeDeploy → Deploy**

### AWS CodePipeline

AWS CodePipeline is a continuous delivery service that automates the workflow between source, build, test, and deployment stages.

**CodePipeline → Automates the CI/CD workflow**

## Jenkins

Jenkins is an automation server used to create CI/CD pipelines and automate activities such as building, testing, and deployment.

## CI/CD Flow with AWS

```text
Developer
    ↓
Source Repository
    ↓
CodePipeline
    ↓
CodeBuild
    ↓
Build & Test
    ↓
CodeDeploy
    ↓
Application


