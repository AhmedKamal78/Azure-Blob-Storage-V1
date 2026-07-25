\# Configuration Details



\## Overview



This document describes the configuration choices made for the Azure Blob Storage V1 project.



The purpose of this configuration was to create a simple, secure, and cost-effective Azure Blob Storage environment while understanding the available storage options.



\---



\# 1. Storage Account Configuration



The Azure Storage Account was configured with settings suitable for a learning and demonstration environment.



\## Basic Configuration



| Setting | Selected Option |

|---|---|

| Storage Type | Azure Blob Storage |

| Performance | Standard |

| Replication | Locally-redundant storage (LRS) |

| Access Tier | Hot |

| Deployment Model | Azure Resource Manager |



\---



\# 2. Performance Configuration



Azure Storage Accounts provide different performance options depending on workload requirements.



\## Selected Option



\*\*Standard Performance\*\*



\### Reason for Selection



Standard performance was selected because this project focuses on learning Blob Storage concepts rather than high-performance workloads.



Advantages:



\- Cost-effective for learning environments

\- Suitable for document and image storage

\- Supports general-purpose cloud storage scenarios



\---



\# 3. Replication Configuration



Azure provides multiple redundancy options to protect stored data.



\## Selected Option



\*\*Locally-redundant storage (LRS)\*\*



\### Description



LRS maintains multiple copies of data within a single Azure datacenter in the same region.



\### Reason for Selection



LRS was selected because:



\- It provides data durability at a lower cost

\- It is sufficient for a development and learning project

\- The project does not require geo-disaster recovery



\---



\# 4. Access Tier Configuration



Azure Blob Storage provides different access tiers based on data usage patterns.



\## Selected Option



\*\*Hot Access Tier\*\*



\### Reason for Selection



The Hot tier was selected because:



\- Files are accessed frequently during testing

\- It provides lower access costs for active data

\- It is suitable for demonstration and development activities



\---



\# 5. Security Configuration



The Storage Account security settings were reviewed to understand Azure storage protection mechanisms.



Configured security considerations:



\- Secure transfer required enabled

\- HTTPS access enforced

\- Public access restricted

\- Storage account access controlled through Azure authentication



\---



\# 6. Blob Container Configuration



The Blob Container was configured for private storage.



| Setting | Configuration |

|---|---|

| Container Access Level | Private |

| Anonymous Access | Disabled |

| Purpose | Store uploaded files |



Private access ensures that stored files are accessible only through authenticated Azure users or applications.



\---



\# 7. Storage Configuration Decisions



The following decisions were made for this V1 implementation:



| Area | Decision | Reason |

|---|---|---|

| Performance | Standard | Suitable for learning and low-cost usage |

| Replication | LRS | Cost-effective local redundancy |

| Access Tier | Hot | Frequent testing and file access |

| Security | Private access | Prevent unauthorized public access |



\---



\# 8. Future Configuration Improvements



Future versions of this project may include:



\- Geo-redundant storage (GRS/GZRS)

\- Lifecycle management policies

\- Azure Entra ID-based access control

\- Role-Based Access Control (RBAC)

\- Customer-managed encryption keys

\- Automated deployment using Infrastructure as Code (IaC)



\---



\# Summary



The Azure Blob Storage V1 configuration was designed to provide a practical understanding of Azure Storage fundamentals while maintaining simplicity, security, and cost efficiency.

