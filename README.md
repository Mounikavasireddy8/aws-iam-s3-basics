# aws-iam-s3-basics
# AWS IAM and S3 Basics

## 📌 Description
This repository demonstrates the core concepts of AWS Identity and Access Management (IAM) and Amazon S3 that are essential for cloud support and junior cloud engineer roles.

The focus is on understanding access control, security best practices, and common real-world use cases.

---

## 🔐 IAM (Identity and Access Management)

### Key Concepts
- **IAM Users**: Created for individual access to AWS services
- **IAM Roles**: Used by AWS services like EC2 to access other services securely
- **IAM Policies**: JSON-based documents that define permissions
- **Least Privilege**: Granting only the permissions required to perform a task

### Real Use Case
- An **EC2 instance accesses an S3 bucket using an IAM Role**
- No access keys are stored on the instance
- This improves security and follows AWS best practices

### Why IAM is Important
- Prevents unauthorized access
- Controls who can do what in AWS
- Mandatory topic in AWS interviews

---

## 📦 Amazon S3 (Simple Storage Service)

### Key Concepts
- **Bucket**: Container for storing objects
- **Object**: Files stored inside a bucket
- **Bucket Policy**: Controls access to the bucket
- **Public vs Private Buckets**

### Versioning
- Keeps multiple versions of objects
- Helps recover from accidental deletion or overwrite
- Uses a **delete marker** instead of permanent deletion

### Static Website Hosting
- S3 can host static websites (HTML, CSS, JS)
- Useful for simple web applications and portfolios

### Common Use Cases
- Backup and restore
- Static website hosting
- Storing logs and application data

---

## 🔗 IAM + S3 Combined Use Case

- EC2 instance launched with an IAM role
- IAM role attached with S3 access policy
- EC2 accesses S3 securely without credentials

This is a common real-world and interview scenario.

---

## 🎯 Key Learnings
- Understood secure access using IAM roles
- Learned how S3 permissions and versioning work
- Applied AWS security best practices
- Gained hands-on experience with core AWS services

---


- IAM controls access to AWS resources
- Roles are preferred over access keys
- S3 is used for storage, backups, and static websites
- Versioning protects data from accidental loss
