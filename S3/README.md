# Amazon S3

## Overview

Amazon Simple Storage Service (S3) is an object storage service used to store and retrieve data from anywhere over the internet.

## Key Concepts

### Bucket

A bucket is a container used to store objects in S3.

### Object

An object is a file stored inside an S3 bucket. It consists of the file itself and its associated metadata.

### Storage Classes

S3 provides different storage classes based on access frequency and storage requirements.

Examples:
- S3 Standard
- S3 Intelligent-Tiering
- S3 Standard-IA
- S3 Glacier

### Bucket Permissions

Access to S3 resources can be controlled using:
- IAM policies
- Bucket policies
- Block Public Access settings
- Access Control Lists (ACLs), where applicable

### Versioning

S3 Versioning keeps multiple versions of an object, helping protect against accidental deletion or overwriting.

### Static Website Hosting

S3 can host static websites containing files such as HTML, CSS, and JavaScript.

## Key Takeaways

- S3 is an object storage service.
- Data is stored as objects inside buckets.
- S3 provides multiple storage classes.
- Access can be controlled using IAM and bucket policies.
- Versioning helps protect stored objects.
- S3 can be used for static website hosting.
