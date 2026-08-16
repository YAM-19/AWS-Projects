# Amazon CloudFront

## What is CloudFront?

Amazon CloudFront is a Content Delivery Network (CDN) provided by AWS.

It delivers content to users from locations closer to them, which can reduce latency and improve performance.

## Why use CloudFront?

- Faster content delivery
- Caches content at Edge Locations
- Reduces requests to the origin
- Improves website performance
- Supports HTTPS and security features

## Basic Architecture

User
↓
CloudFront
↓
Edge Location
↓
Origin (S3 / EC2 / other AWS service)

## Important Terms

### CDN
Content Delivery Network.

### Origin
The original location where the content is stored.

### Edge Location
A location where CloudFront caches content closer to users.

### Cache
A temporary copy of content stored by CloudFront.

## CloudFront + S3

User
↓
CloudFront
↓
S3 Bucket
↓
Website Files
