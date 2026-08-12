# AWS Identity and Access Management (IAM)

## Overview

AWS Identity and Access Management (IAM) is used to securely control access to AWS resources.

## Key Concepts

### IAM User

An IAM user represents a person or application that needs access to AWS resources.

### IAM Group

A group is a collection of IAM users. Permissions can be assigned to the group so that users in the group receive those permissions.

### IAM Policy

A policy is a JSON document that defines what actions are allowed or denied on AWS resources.

### IAM Role

An IAM role provides temporary permissions that can be assumed by AWS services, applications, or users.

### Root User

The AWS account root user has full access to the AWS account. It should not be used for everyday AWS tasks.

## Principle of Least Privilege

Users and services should receive only the permissions they actually need.

This helps reduce security risks.

## Important IAM Components

- Users
- Groups
- Policies
- Roles
- Permissions
- Least Privilege

## Key Takeaways

- IAM controls access to AWS resources.
- Policies define permissions.
- Groups help manage permissions for multiple users.
- Roles provide temporary access without sharing long-term credentials.
- The principle of least privilege improves security.
