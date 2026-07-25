# Lessons Learned

## Overview

This document summarizes the key learnings and observations from implementing the Azure Blob Storage V1 project.

---

## Key Learnings

### Azure Resource Hierarchy

Understood the relationship between:

```
Azure Subscription → Resource Group → Storage Account → Blob Container → Files
```

---

### Azure Blob Storage Concepts

Learned the core components of Azure Blob Storage:

- Storage Account
- Blob Container
- Blobs (files)
- Access tiers
- Replication options

---

### Azure Portal vs Storage Explorer

Observed the difference between the two tools:

**Azure Portal**
- Used for creating and configuring Azure resources

**Azure Storage Explorer**
- Used for managing files and Blob Storage data

---

### Configuration Decisions

Learned that storage configuration depends on requirements:

- Performance affects workload suitability
- Replication affects availability and cost
- Access tier affects storage and access costs
- Security settings control data protection

---

## Challenges and Observations

- Understanding the Azure hierarchy required careful attention.
- Storage Account names must be globally unique.
- Azure provides many configuration options, requiring informed decisions.
- Storage Explorer provides a convenient way to manage blob files.

---

## Overall Outcome

This project provided practical experience in:

- Creating Azure Storage resources
- Configuring Blob Storage
- Managing cloud storage using Azure tools
- Documenting an Azure infrastructure project

---

## Future Learning

This project provides a foundation for future implementations:

- C# application integration with Azure Storage
- ASP.NET Core API development
- Microsoft Entra ID authentication
- Infrastructure as Code (IaC)
- CI/CD automation