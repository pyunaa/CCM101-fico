# Mission Reflection

This laboratory activity helped me understand why object storage is commonly used for applications that need to manage large amounts of unstructured data. Object storage is better suited for storing millions of photos because it is designed to store files as objects and organize them inside buckets. Unlike traditional block storage, object storage can be accessed through APIs and is designed to handle large collections of files such as images, videos, backups, and documents.

Docker made deploying the MinIO storage server easier because I did not need to manually install and configure all of the software and its dependencies. With a single Docker command, I was able to download the MinIO image, create a container, configure the required ports, set the administrator credentials, and start the storage service. This showed me how containers can make cloud services easier to deploy and reproduce.

A bucket is a storage container used by object storage systems to organize objects such as images and documents. In this activity, I created a bucket named `client-photos` and uploaded a sample file to verify that the MinIO server was working correctly.

Large enterprise companies can protect their object storage data from physical server failures by using redundancy, replication, backups, and distributed storage systems. Data can be stored across multiple physical servers or locations so that the failure of one server does not necessarily result in the loss of the stored data. Organizations can also use monitoring and recovery systems to detect failures and restore data when necessary.

My confidence in navigating the Linux command line is also growing. At the beginning, commands such as Docker commands were unfamiliar, but following the deployment process helped me understand how commands control containers and services. I am becoming more comfortable entering commands, checking container status, and troubleshooting basic deployment issues. This activity also helped me see how Linux, Docker, and cloud storage technologies work together in a practical cloud environment.
