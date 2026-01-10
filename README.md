# object-storage-backend-aws
Secure Object Storage Access Backend on AWS

Build a cost-capped, least-privilege backend on AWS that lets internal developers upload, list, and retrieve private S3 objects with zero public exposure and single-instance failure tolerance.

Below image shows architecture of how first version works: 
<img width="847" height="191" alt="image" src="https://github.com/user-attachments/assets/bb01c53d-0220-4f09-8b28-ef1d0ea5d37b" />

Users through API Gateway access the S3 objects.
