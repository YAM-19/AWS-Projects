# AWS Secrets Management

## Overview

AWS Secrets Management is used to securely store and manage sensitive information such as passwords, API keys, access tokens, and credentials.

## AWS Secrets Management Solutions

### AWS Systems Manager Parameter Store

Used to securely store configuration values and parameters.

Examples:
- Usernames
- Registry URLs
- Application configuration
- Environment-specific values

### AWS Secrets Manager

Used for highly sensitive information such as:

- Database passwords
- API tokens
- Credentials

Key feature:
- Automatic secret rotation

### HashiCorp Vault

A platform-independent secrets management solution commonly used for:

- Multi-cloud environments
- Hybrid-cloud environments
- On-premise infrastructure

## Parameter Store vs Secrets Manager

| Parameter Store | Secrets Manager |
|---|---|
| Configuration values | Sensitive secrets |
| Lower cost | Higher cost |
| Simple use cases | Advanced secret management |
| Basic parameters | Passwords and API tokens |
| Limited rotation | Automatic secret rotation |

## Secret Rotation

Secret rotation means regularly changing a secret to a new value.

Example:

Old Password → Rotation → New Password

This improves security by reducing the time a compromised secret remains valid.

## CI/CD Use Case

A CI/CD pipeline can use:

Developer → GitHub → Jenkins → AWS

- Basic configuration → Parameter Store
- Sensitive passwords/API tokens → Secrets Manager

## Key Takeaways

- Never hard-code passwords or API keys in source code.
- Use Parameter Store for configuration values.
- Use Secrets Manager for highly sensitive secrets.
- Secret rotation improves security.
- HashiCorp Vault is useful for multi-cloud environments.
