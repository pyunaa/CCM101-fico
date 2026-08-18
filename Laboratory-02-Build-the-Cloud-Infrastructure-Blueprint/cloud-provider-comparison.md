# Cloud Provider Comparison

## Core Infrastructure Services

| Infrastructure Component | AWS | Microsoft Azure | Google Cloud Platform |
|---|---|---|---|
| **Compute** | **Amazon EC2 (Elastic Compute Cloud)** – provides scalable virtual computing capacity and virtual servers. | **Azure Virtual Machines** – provides scalable virtual machines with different CPU, memory, storage, and networking configurations. | **Compute Engine** – provides scalable virtual machine and bare-metal instances. |
| **Storage** | **Amazon S3 (Simple Storage Service)** – object storage for storing and protecting data in buckets. | **Azure Blob Storage** – object storage for large amounts of unstructured data such as files, images, and videos. | **Cloud Storage** – managed object storage that stores data in buckets. |
| **Networking** | **Amazon VPC (Virtual Private Cloud)** – provides an isolated virtual network with subnets, routing, IP addresses, and gateways. | **Azure Virtual Network (VNet)** – provides private networking for Azure resources, including subnets, IP addresses, routing, and security. | **Virtual Private Cloud (VPC)** – provides scalable networking for Compute Engine, GKE, and other Google Cloud resources. |
| **Identity and Access Management (IAM)** | **AWS IAM** – manages authentication, authorization, users, roles, and permissions for AWS resources. | **Microsoft Entra ID + Azure RBAC** – manages identities and controls access to Azure resources through roles and permissions. | **Cloud IAM** – controls who can access Google Cloud resources and what actions they can perform. |

## Guide Questions

### 1. Which cloud provider offers the broadest range of services? Explain your answer.

**Amazon Web Services (AWS)** is generally recognized as having the broadest range of cloud services among the three major providers. Its services cover computing, storage, networking, databases, security, analytics, AI/ML, IoT, and many other areas.

### 2. Which cloud platform would you recommend for an organization that primarily uses Microsoft products? Why?

**Microsoft Azure** would be a strong recommendation for an organization that primarily uses Microsoft products. Azure works closely with Microsoft technologies such as Windows Server, Microsoft 365, .NET, and Microsoft Entra ID, making integration easier.

### 3. Which platform is widely recognized for Artificial Intelligence (AI), Machine Learning (ML), and Kubernetes services?

**Google Cloud Platform (GCP)** is widely recognized for its strengths in AI, ML, and Kubernetes. Google developed Kubernetes, and Google Cloud provides **Google Kubernetes Engine (GKE)** along with various AI and machine learning services.

### 4. What similarities did you observe among the three cloud providers?

All three cloud providers offer similar core infrastructure services for compute, storage, networking, and identity and access management. They provide scalable and virtualized resources that allow organizations to run applications and store data without maintaining their own physical data-center infrastructure.

## References

1. Amazon Web Services. (n.d.). *What is Amazon EC2?* https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html
2. Amazon Web Services. (n.d.). *What is Amazon S3?* https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html
3. Amazon Web Services. (n.d.). *What is Amazon VPC?* https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html
4. Amazon Web Services. (n.d.). *What is IAM?* https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html
5. Microsoft. (n.d.). *Overview of virtual machines in Azure.* https://learn.microsoft.com/en-us/azure/virtual-machines/overview
6. Microsoft. (n.d.). *About Blob (object) storage.* https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-overview
7. Microsoft. (n.d.). *What is Azure Virtual Network?* https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview
8. Microsoft. (n.d.). *What is Microsoft Entra?* https://learn.microsoft.com/en-us/entra/fundamentals/what-is-entra
9. Google Cloud. (n.d.). *Compute Engine overview.* https://docs.cloud.google.com/compute/docs/overview
10. Google Cloud. (n.d.). *Cloud Storage.* https://cloud.google.com/storage
11. Google Cloud. (n.d.). *Virtual Private Cloud overview.* https://docs.cloud.google.com/vpc/docs/overview
12. Google Cloud. (n.d.). *Identity and Access Management documentation.* https://docs.cloud.google.com/iam/docs
