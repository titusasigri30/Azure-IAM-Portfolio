# Identity Foundation

## Project Overview

This project establishes the Microsoft Entra ID identity foundation for
Ability_Enterprise, a Financial Services organization used throughout this
IAM portfolio.

The project demonstrates the initial design of users, groups, identity
structure, device identity, and access-management principles.

## Business Scenario

Ability_Enterprise with approximately
500 employees.

The organization contains:

- IT
- HR
- Finance
- Sales
- External contractors
  
The organization uses Microsoft Entra ID as its identity platform.

## Objectives

The Identity Foundation project establishes:

- Microsoft Entra ID
- Users
- Security groups
- Department-based identity organization
- Device identity awareness
- IAM architecture
- Group-based access management
- Least-privilege principles

## Initial Users

| User | Department | Purpose |
|---|---|---|
| Alice Joe, Comfort Mills, Emma Asig| HR | HR employee |
| Bob Morgan, Smith Jules, Joseph Derik | IT | IT administration scenario |
| Carol John, Juan Jack, Pat York | Finance | Finance employee |
| David Ires, Brat Johnson, Mike Dutch, Zahn Chana| Sales | Sales employee |
| Eve Schules, Myrs Deven, Alina Breden | Contractor | Contractor scenario |

## Initial Groups

The following security groups are used:

- GRP-HR-Users
- GRP-IT-Users
- GRP-Finance-Users
- GRP-Sales-Users
- GRP-Contractors

## Access Management Principle

Where practical, access will be managed through security groups rather
than directly assigned to individual users.

This provides a foundation for:

- RBAC
- JML
- License management
- Conditional Access
- Application access
- Access packages
- Access reviews

## Device Identity

Devices will be treated as an additional security context alongside
users and groups.

Later projects will demonstrate the relationship between:

User identity

Device identity

Device management and compliance

Conditional Access

Application access

## Security Principles

The lab follows these principles:

- Least privilege
- Group-based access management
- Separation of duties
- Strong authentication
- Lifecycle-based access
- Device-aware access
- Privileged access management
- Regular access reviews
- Auditing and monitoring

## Evidence

Evidence for this project will include:

- IAM architecture diagram
- IAM matrix
- Entra ID configuration screenshots
- User configuration
- Group configuration
- Group membership
- Demonstration video

## Disclaimer

This is created for educational and professional portfolio purposes.

No real customer data, credentials, secrets, or sensitive organizational
information is stored in this repository.
