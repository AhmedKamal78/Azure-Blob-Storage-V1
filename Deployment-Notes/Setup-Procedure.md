\# Setup Procedure



\## Overview



This document describes the step-by-step procedure used to create and configure the Azure Blob Storage V1 environment.



The implementation was performed using the Azure Portal and Azure Storage Explorer.



\---



\# 1. Create Azure Resource Group



A Resource Group was created to logically organize and manage all Azure resources related to this project.



\### Resource Group Details



| Setting | Value |

|---|---|

| Subscription | Azure Pay-As-You-Go |

| Resource Group Name | IntroAzureRG |

| Region | UAE North |



\### Procedure



1\. Sign in to the Azure Portal.

2\. Navigate to \*\*Resource Groups\*\*.

3\. Select \*\*Create\*\*.

4\. Select the required subscription.

5\. Enter the Resource Group name.

6\. Select the deployment region.

7\. Review and create the Resource Group.



\---



\# 2. Create Azure Storage Account



An Azure Storage Account was created inside the Resource Group to provide cloud-based object storage.



\### Procedure



1\. Open the created Resource Group.

2\. Select \*\*Create a resource\*\*.

3\. Search for \*\*Storage Account\*\*.

4\. Select \*\*Create\*\*.

5\. Configure the basic storage settings:



| Setting | Value |

|---|---|

| Subscription | Azure Pay-As-You-Go |

| Resource Group | IntroAzureRG |

| Storage Account Name | <storage-account-name> |

| Region | UAE North |

| Performance | Standard |

| Redundancy | Locally-redundant storage (LRS) |



6\. Review the configuration.

7\. Create the Storage Account.



\---



\# 3. Configure Storage Account Settings



After creation, the Storage Account settings were reviewed and configured according to project requirements.



The following areas were verified:



\- Performance configuration

\- Replication option

\- Access tier

\- Security settings

\- Data protection options



Detailed configuration choices are documented separately in:



```

Configuration-Details.md

```



\---



\# 4. Create Blob Container



A Blob Container was created to store files and demonstrate Azure Blob Storage functionality.



\### Procedure



1\. Open the Storage Account.

2\. Navigate to:



```

Data Storage → Containers

```



3\. Select \*\*+ Container\*\*.

4\. Enter the container name.

5\. Select the required anonymous access level.

6\. Create the container.



\### Container Details



| Setting | Value |

|---|---|

| Storage Account | <storage-account-name> |

| Container Name | <container-name> |

| Access Level | Private |



\---



\# 5. Upload Files to Blob Storage



Files were uploaded to the Blob Container to validate storage functionality.



\### Using Azure Portal



1\. Open the Blob Container.

2\. Select \*\*Upload\*\*.

3\. Choose files from the local system.

4\. Start the upload operation.

5\. Verify that files appear in the container.



\### Using Azure Storage Explorer



1\. Connect Azure Storage Explorer to the Azure account.

2\. Locate the Storage Account.

3\. Open the Blob Container.

4\. Upload files using drag-and-drop.

5\. Verify successful upload.



\---



\# 6. Verify Deployment



The following checks were performed after deployment:



\- Resource Group was available.

\- Storage Account was successfully created.

\- Blob Container was accessible.

\- Uploaded files were visible.

\- Azure Portal and Storage Explorer showed consistent data.



\---



\# Final Environment State



The completed Azure Blob Storage V1 environment contains:



```

Azure Subscription

&#x20;       |

&#x20;       └── Resource Group

&#x20;               |

&#x20;               └── Storage Account

&#x20;                       |

&#x20;                       └── Blob Container

&#x20;                               |

&#x20;                               └── Uploaded Files

```



This completes the setup procedure for the Azure Blob Storage V1 project.

