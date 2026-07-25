# Azure Blob Storage V1

## Overview

This project demonstrates a basic Azure cloud storage solution using Azure Blob Storage.

The objective is to design and implement a simple, scalable, and reliable cloud storage architecture for storing documents, images, and other files using Microsoft Azure.

This project focuses on understanding Azure Storage hierarchy, Blob Storage concepts, Azure resource organization, and documenting cloud implementations.

---

## Architecture

The solution consists of:

- User
- Azure Storage Account
- Azure Blob Storage
- Blob Container
- Blob Objects (documents, images, and other files)

Architecture flow:

User → Azure Storage Account →  Azure Blob Storage → Azure Storage Container → Blobs

---

## Architecture Diagram

![Azure Blob Storage Architecture](Architecture/Azure-Blob-Storage-Architecture-V1.png)

---

## Azure Services Used

- Azure Storage Account
- Azure Blob Storage
- Azure Blob Container
- Azure Storage Explorer

---

| Resource Type | Resource Name |
|---|---|
| Resource Group | rg-azure-blob-storage-v1 |
| Storage Account | akblobstorev1 |
| Blob Container | sample-files |

---

# Screenshots

## 1. Resource Group Overview

![Resource Group Overview](Documentation/Screenshots/01-resource-group-overview.png)

---

## 2. Blob Storage Settings

![Blob Storage Settings](Documentation/Screenshots/02-blob-storage-settings.png)

---

## 3. Blob Containers List

![Blob Containers List](Documentation/Screenshots/03-blob-containers-list.png)

Note:
- `$logs` is an Azure-managed system container.
- `sample-files` is the project Blob container created for application data.

---

## 4. Blob Container with Uploaded Files

![Sample Files Container](Documentation/Screenshots/04-sample-files-container.png)

---

## 5. Azure Storage Explorer Verification

![Azure Storage Explorer](Documentation/Screenshots/05-storage-explorer.png)

---

## Learning Outcomes

- Understanding Azure Storage hierarchy
- Understanding the relationship between Storage Accounts, Containers, and Blobs
- Learning basic cloud architecture design
- Creating and documenting Azure resources
- Using Azure Portal and Azure Storage Explorer
- Building a foundation for future Azure projects

---

## Documentation

Detailed project documentation is available in:

- [Setup Procedure](Documentation/Setup-Procedure.md)
- [Configuration Details](Documentation/Configuration-Details.md)
- [Lessons Learned](Documentation/Lessons-Learned.md)
- [Deployment Guide](Deployment-Notes/Deployment-Guide.md)

---

## Future Enhancements

Planned upgrades:

- **V2:** Add C# Console uploader using Azure SDK
- **V3:** Add WinUI 3 frontend
- **V4:** Add ASP.NET Core API
- **V5:** Enterprise version with Entra ID authentication, Key Vault, monitoring, logging, and CI/CD