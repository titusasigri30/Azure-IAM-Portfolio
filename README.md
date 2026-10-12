**Azure IAM Portfolio**

A hands-on Microsoft Entra ID and Azure Identity and Access Management (IAM) portfolio demonstrating identity lifecycle management, authentication, authorization, governance, privileged access, external identities, device-aware access, automation, and monitoring.

**Overview**

This repository documents a practical Microsoft Entra ID and Azure IAM laboratory designed to demonstrate skills relevant to junior IAM administrator and identity support roles. The laboratory uses Ability_Enterprise, a fictional financial services organization, to model realistic enterprise identity and access management scenarios. The portfolio is developed progressively over 30 days, with an emphasis on hands-on implementation, security best practices, troubleshooting, automation, and technical documentation.

**Organization Scenario**

Ability_Enterprise — Fictional Financial Services Organization

The simulated environment represents an organization with:
Approximately 500 employees in the scenario
IT, HR, Finance, and Sales departments
External contractors and guest users
Corporate devices and device-aware access requirements
SaaS applications and enterprise SSO
Privileged administrators
Identity governance and compliance requirements

The scenario is used for educational purposes. The simulated organization size does not represent the number of actual users in the laboratory tenant.

**IAM Capabilities**

This portfolio aims to demonstrate the following capabilities through practical labs, documented scenarios, and testing evidence.
Identity and Access Management
Microsoft Entra ID users and groups
Identity lifecycle management: Joiner, Mover, Leaver (JML)
Role-Based Access Control (RBAC)
Administrative units and least privilege
License assignment, modification, reporting, automation, and reclamation
Authentication and Application Access
Multi-Factor Authentication (MFA)
Self-Service Password Reset (SSPR)
Conditional Access and sign-in troubleshooting
FIDO2, passkeys, and phishing-resistant authentication
Device identity and device-aware access, where supported
Single Sign-On (SSO)
SAML and WS-Federation
OAuth 2.0 and OpenID Connect (OIDC)
External Identities
Microsoft Entra B2B collaboration
External user lifecycle management
Cross-tenant access and collaboration
External identity provider concepts
Azure Workload Security
Azure Key Vault: secrets, keys, certificates, and access control
Managed identities and passwordless workload access
Azure RBAC and least-privilege permissions
Identity Governance and Privileged Access
Privileged Identity Management (PIM)
Eligible and time-limited privileged role assignments
Entitlement management and access packages
Access reviews and removal of unnecessary access
Automation and Monitoring
Microsoft Graph PowerShell
Identity and license reporting
Sign-in, audit, and provisioning logs
Log Analytics and Kusto Query Language (KQL)
Monitoring and investigation scenarios

Feature availability depends on the tenant configuration, permissions, subscription, and licensing. Any feature that cannot be deployed will be clearly identified as a design exercise or partially implemented scenario.

**Portfolio Approach**

Each project follows a practical IAM engineering workflow:
Business problem and requirements
Architecture and design
Prerequisites and licensing requirements
Configuration and implementation
Testing and expected results
Troubleshooting and investigation
Security considerations and least privilege
Automation, where applicable
Monitoring and evidence, where applicable
Documentation and lessons learned
Projects

Projects will be added progressively as the laboratory is built. Each project will include relevant documentation, architecture, configuration steps, testing evidence, screenshots, and PowerShell or KQL scripts where applicable.

#	Project	Status
01	Identity Foundation & RBAC	🔄 In Progress
02	Identity Lifecycle Management (Joiner–Mover–Leaver)	⏳ Planned
03	License Management & Reporting	⏳ Planned
04	Authentication & Access Control	⏳ Planned
05	Single Sign-On (SSO) Fundamentals & Troubleshooting	⏳ Planned
06	Federation & Application Protocols	⏳ Planned
07	External Identities & Cross-Tenant Access	⏳ Planned
08	Azure Key Vault & Managed Identities	⏳ Planned
09	Identity Governance & Privileged Access	⏳ Planned
10	IAM Monitoring, PowerShell & KQL	⏳ Planned
11	End-to-End IAM Capstone	⏳ Planned

**Project scope**

Project 04 includes MFA, SSPR, Conditional Access, FIDO2, and device-aware access where supported.
Project 06 covers SAML, WS-Federation, OAuth 2.0, and OIDC.
Project 09 covers PIM, access packages, and access reviews.
Portfolio Demonstration Videos

Three polished demonstration videos will be produced as the projects are completed.

#	Video	Status
01	Identity Lifecycle & License Management	⏳ Planned
02	Authentication, Access Control & SSO	⏳ Planned
03	End-to-End IAM Capstone & Monitoring	⏳ Planned

Videos will demonstrate actual configurations and test results where available. Design-only or simulated scenarios will be identified clearly.

Video links will be added here when recordings are published.

**Technologies**
Microsoft Entra ID
Microsoft Azure
Microsoft Graph
Microsoft Graph PowerShell
PowerShell
Kusto Query Language (KQL)
Azure Key Vault
Microsoft Intune concepts, where relevant to device-aware access
Security and Data Handling

This repository is intended for educational and professional portfolio purposes.

No real customer data, passwords, credentials, access tokens, private keys, or application secrets will be committed.
Screenshots and logs will be sanitized before publication.
Test accounts and fictional organizational data will be used.
Scripts that modify users, groups, licenses, or access will be tested carefully and documented.
Project status will reflect actual implementation and verification.
Project Status

The portfolio is being developed progressively over 30 days. Planned projects will be marked as completed only after their implementation or documented alternative has been reviewed and their stated results verified.

The objective is to build demonstrable practical skills in Microsoft Entra ID administration, identity lifecycle management, license administration, authentication, governance, automation, monitoring, and IAM troubleshooting.
