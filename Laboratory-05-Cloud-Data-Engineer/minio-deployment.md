# MinIO Deployment

## Deployment Overview

For this laboratory activity, I deployed MinIO as an S3-compatible object storage server using Docker. The MinIO server was configured with separate ports for the storage API and web-based management console.

## Docker Command

The following Docker command was used to deploy the MinIO server:

```bash
sudo docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
codemowers/minio:RELEASE.2025-09-07T16-13-09Z server /data --console-address ":9001"
```

## Port Configuration

Two ports were configured during deployment:

| Port     | Purpose                                    |
| -------- | ------------------------------------------ |
| **9000** | MinIO API and object storage communication |
| **9001** | MinIO Web Console                          |

The web-based MinIO management console was accessed using port **9001** through the KillerCoda port forwarding feature.

## Bucket Created

The storage bucket created during the laboratory activity was:

```text
client-photos
```

A test file was uploaded to the bucket to verify that the object storage server was functioning correctly.

##  What the -e flags (Environment Variables) did in Docker command?

The -e option in Docker is used to define environment variables that are passed to the container when it starts.
