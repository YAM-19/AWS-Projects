# AWS Cost Optimization – Stale EBS Snapshot Cleanup

## 📌 Overview

This project uses **AWS Lambda** to automate the cleanup of unused or orphaned **Amazon EBS snapshots**.

The goal is to reduce unnecessary AWS storage usage and help optimize cloud costs.

## 🎯 Problem

Unused EBS snapshots can remain in an AWS account even after their associated EBS volumes are no longer being used.

These snapshots continue to consume storage, which can lead to unnecessary costs.

## 💡 Solution

I created an **AWS Lambda function using Python and Boto3** to:

* Retrieve EBS snapshots owned by the AWS account.
* Check the EBS volume associated with each snapshot.
* Identify snapshots whose associated volume is no longer attached.
* Delete stale/orphaned snapshots automatically.
* Record Lambda execution information in CloudWatch.

## 🏗️ Architecture

```text
EBS Snapshots
      ↓
AWS Lambda
      ↓
Check Associated EBS Volume
      ↓
Identify Stale/Orphaned Snapshot
      ↓
Delete Snapshot
      ↓
Reduce Unnecessary Storage Costs
```

## 🛠️ AWS Services Used

* **AWS Lambda** – Runs the cleanup automation.
* **Amazon EC2** – Provides instance information.
* **Amazon EBS** – Stores volumes and snapshots.
* **Amazon CloudWatch** – Monitors Lambda execution and logs.
* **AWS IAM** – Provides the required permissions for Lambda.

## 💻 Technologies Used

* Python
* Boto3
* AWS Lambda
* AWS Management Console

## ⚙️ How It Works

1. Lambda retrieves all EBS snapshots owned by the account.
2. It retrieves running EC2 instances.
3. It checks the EBS volume associated with each snapshot.
4. If the volume has no attachment, the snapshot is considered stale.
5. If the associated volume no longer exists, the snapshot is also considered stale.
6. Lambda deletes the stale snapshot.
7. The execution is recorded in CloudWatch Logs.

## 🧪 Testing

The Lambda function was successfully deployed and tested.

CloudWatch Logs were used to verify the Lambda execution.

The test environment included a temporary EBS snapshot that was cleaned up through the automation.

## 📊 Result

The project demonstrates how **AWS Lambda can automate cloud cost optimization** by identifying and removing unnecessary EBS snapshots.

This reduces manual cleanup work and helps prevent unnecessary storage usage.

## 📚 What I Learned

* AWS Lambda and serverless architecture
* Boto3 and AWS SDK for Python
* EBS volumes and snapshots
* Lambda IAM permissions
* CloudWatch logging
* AWS resource automation
* Cloud cost optimization

## ✅ Project Status

**Completed**
