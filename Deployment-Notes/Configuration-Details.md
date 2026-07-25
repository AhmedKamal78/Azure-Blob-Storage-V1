\# Configuration Details



\## Overview



This document summarizes the main configuration choices made for the Azure Blob Storage V1 project.



\---



\## Storage Account Configuration



| Setting | Selected Option |

|---|---|

| Storage Type | Azure Blob Storage |

| Performance | Standard |

| Replication | Locally-redundant storage (LRS) |

| Access Tier | Hot |



\---



\## Configuration Decisions



\### Performance



\*\*Standard\*\*



Selected because it provides a cost-effective solution suitable for learning, testing, and general storage workloads.



\---



\### Replication



\*\*Locally-redundant storage (LRS)\*\*



Selected because it provides data redundancy within the Azure region while keeping costs low.



\---



\### Access Tier



\*\*Hot\*\*



Selected because project files are accessed frequently during testing and demonstration.



\---



\## Security Settings



Configured security options:



\- Secure transfer required: Enabled

\- Blob Container access: Private

\- Public anonymous access: Disabled



\---



\## Summary



The V1 configuration was designed to provide a simple, secure, and cost-effective Azure Blob Storage implementation while understanding the key storage options available in Azure.

