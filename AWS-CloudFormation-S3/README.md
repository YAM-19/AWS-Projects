# AWS CloudFormation – Infrastructure as Code

## 📌 Overview

This project is based on learning **Infrastructure as Code (IaC)** using **AWS CloudFormation**.

I created a CloudFormation Template (CFT) using YAML, deployed it as a CloudFormation stack, created an S3 bucket through the stack, and performed drift detection.

## 🛠️ AWS Services Used

* AWS CloudFormation
* Amazon S3

## 📚 Topics Learned

### Infrastructure as Code (IaC)

Infrastructure as Code is the practice of defining and managing infrastructure using code instead of manually creating resources through the AWS Console.

### CloudFormation Template (CFT)

AWS CloudFormation Templates are used to define AWS resources in YAML or JSON.

In this project, a simple YAML template was used to define an S3 bucket.

### CloudFormation Stack

The CloudFormation template was used to create a **CloudFormation stack**.

The stack then created the S3 bucket defined in the template.

### Drift Detection

CloudFormation **drift detection** was performed to check whether the actual AWS resource had changed from the configuration defined in the CloudFormation template.

## 🔄 Project Workflow

```text
CloudFormation Template (YAML)
            ↓
     CloudFormation Stack
            ↓
          S3 Bucket
            ↓
      Drift Detection
```

## 📂 Files

```text
AWS-CloudFormation-S3/
├── template.yaml
└── README.md
```

## 🎯 Key Takeaways

* Understood the concept of Infrastructure as Code.
* Learned the basics of AWS CloudFormation.
* Created an AWS resource using a CloudFormation Template.
* Learned how CloudFormation stacks work.
* Performed drift detection.
* Gained a basic understanding of **CloudFormation vs Terraform**.

## 🚀 Next Steps

* Learn more CloudFormation template components.
* Work with multiple AWS resources in a single template.
* Explore parameters, outputs, and intrinsic functions.
* Learn Terraform as another Infrastructure as Code tool.
