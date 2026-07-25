# Lessons Learned

## Overview

This document summarizes the key concepts, practical observations, and challenges encountered while implementing the Azure Blob Storage V1 project.

The objective of this project was not only to create cloud storage resources but also to develop a better understanding of Azure storage architecture and management practices.

---

# 1. Understanding Azure Resource Hierarchy

One of the key learnings from this project was understanding the relationship between different Azure components.

The Azure hierarchy follows this structure:

```
Microsoft Entra ID Tenant
        |
        └── Azure Subscription
                |
                └── Resource Group
                        |
                        └── Storage Account
                                |
                                └── Blob Container
                                        |
                                        └── Blobs (Files)
```

### Key Observation

Azure resources are organized through a logical hierarchy. A Resource Group acts as a management boundary for related resources, while the Storage Account provides the actual storage service.

---

# 2. Understanding Azure Blob Storage Concepts

This project provided practical understanding of Azure Blob Storage components:

## Storage Account

The Storage Account is the primary Azure resource that provides access to storage services.

## Blob Container

A Blob Container works as a logical grouping mechanism for stored objects.

## Blobs

Blobs are the actual files stored inside containers, such as:

- Images
- Documents
- Videos
- Backup files

---

# 3. Azure Portal vs Azure Storage Explorer

Both Azure Portal and Azure Storage Explorer were used during this project.

## Azure Portal

Advantages:

- Complete Azure resource management
- Easy configuration of settings
- Useful for learning Azure services

## Azure Storage Explorer

Advantages:

- Desktop-based storage management tool
- Easier file upload and download operations
- Better experience for managing multiple storage resources

### Observation

Azure Portal is better for infrastructure configuration, while Storage Explorer provides a more convenient experience for day-to-day file management.

---

# 4. Understanding Storage Configuration Choices

The project improved understanding of Azure storage configuration decisions.

## Performance

Standard performance is suitable for general-purpose storage scenarios and provides a cost-effective option.

## Replication

Different replication options provide different levels of availability and durability.

## Access Tier

Access tiers should be selected according to data usage patterns:

- Hot: Frequently accessed data
- Cool: Infrequently accessed data
- Archive: Long-term storage

---

# 5. Security Awareness

The project highlighted the importance of securing cloud storage resources.

Important considerations learned:

- Avoid unnecessary public access
- Use authentication-based access
- Enable secure transfer
- Understand access control mechanisms

---

# 6. Challenges and Observations

During implementation, the following practical observations were made:

- Understanding the relationship between Tenant, Subscription, Resource Group, and Resources required careful attention.
- Storage Account naming rules must be followed because names are globally unique.
- Azure Portal provides many options, which can initially be overwhelming.
- Choosing the correct storage configuration depends on workload requirements.

---

# 7. Overall Learning Outcome

After completing this project, the following skills were developed:

- Understanding Azure Storage architecture
- Creating and configuring Azure Blob Storage
- Managing resources through Azure Portal
- Using Azure Storage Explorer
- Understanding storage performance, replication, and access tiers
- Documenting cloud infrastructure projects professionally

---

# Future Learning Direction

This project provides the foundation for future Azure implementations:

- Developing applications using Azure Storage SDKs
- Implementing authentication with Microsoft Entra ID
- Creating APIs with ASP.NET Core
- Automating deployment using Infrastructure as Code
- Integrating CI/CD pipelines

---

# Conclusion

Azure Blob Storage V1 provided practical exposure to cloud storage concepts and established a foundation for building more advanced Azure solutions.