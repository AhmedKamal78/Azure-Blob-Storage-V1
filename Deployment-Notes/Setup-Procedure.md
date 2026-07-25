# Setup Procedure

## Overview

This document describes the steps performed to create the Azure Blob Storage V1 environment.

---

## Deployment Steps

### 1. Create Resource Group

Created an Azure Resource Group to organize all project resources.

**Details:**

| Setting | Value |
|---|---|
| Resource Group | rg-azure-blob-storage-v1 |
| Region | West US 3 |

---

### 2. Create Storage Account

Created an Azure Storage Account inside the Resource Group.

Configured:

- Performance: Standard
- Replication: LRS
- Access Tier: Hot

---

### 3. Create Blob Container

Created a Blob Container for storing files.

Configuration:

- Container Access: Private
- Anonymous Access: Disabled

---

### 4. Upload Files

Uploaded sample files to the Blob Container using:

- Azure Portal
- Azure Storage Explorer

---

## Final Environment

Azure Subscription → Resource Group → Storage Account → Blob Container → Files
```

---

## Result

Azure Blob Storage V1 environment was successfully created and validated.