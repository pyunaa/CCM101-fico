# Storage Types Research

## Comparison of Cloud Storage Types

| Storage Type       | Description                                                                                                                            | Primary Use Case                                                                                      | Cloud Provider Example             |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | ---------------------------------- |
| **Block Storage**  | Stores data in fixed-size blocks that can be independently managed and accessed by a computer or virtual machine.                      | Best for operating systems, databases, and applications that require fast and consistent disk access. | AWS Elastic Block Store (EBS)      |
| **File Storage**   | Stores data as files organized into folders and directories. Multiple users or systems can access the same file system over a network. | Best for shared files, documents, media files, and applications that need a shared file system.       | AWS Elastic File System (EFS)      |
| **Object Storage** | Stores data as objects together with metadata and a unique identifier inside a storage container called a bucket.                      | Best for large amounts of unstructured data such as images, videos, backups, and documents.           | Amazon Simple Storage Service (S3) |

## Why Object Storage is Best for the Client

Object Storage is well suited for the client's photo-sharing application because it is designed to store large amounts of unstructured data such as user-uploaded images. It also allows applications to access files through an API while organizing data into buckets, making it practical for a system that may eventually contain millions of photos.
