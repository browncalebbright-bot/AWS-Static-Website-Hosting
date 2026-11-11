# AWS Static Website Hosting

## Project Overview

This project demonstrates the deployment of a static website using Amazon Web Services (AWS). The solution uses Amazon S3 for website hosting, CloudFront for content delivery, Route 53 for DNS management, and IAM for secure access control.

The architecture provides a scalable, cost-effective, and globally distributed web hosting solution.

## Architecture

```text
User
 │
 ▼
Route 53
 │
 ▼
CloudFront Distribution
 │
 ▼
S3 Bucket
 │
 ▼
Static Website Files
```

## Business Objective

The objective of this project was to deploy a secure and highly available static website using AWS services while improving performance through global content delivery.

## Technologies Used

- Amazon S3
- Amazon CloudFront
- Amazon Route 53
- AWS IAM
- AWS Management Console
- Static Website Hosting

## Implementation Steps

1. Created an Amazon S3 bucket
2. Uploaded static website files
3. Enabled static website hosting
4. Configured bucket permissions
5. Created a CloudFront distribution
6. Configured CloudFront origin settings
7. Configured Route 53 DNS records
8. Implemented IAM least-privilege access
9. Tested website accessibility and content delivery

## Skills Demonstrated

- AWS Cloud Fundamentals
- S3 Storage Management
- Content Delivery Networks (CDN)
- DNS Management
- IAM Security Principles
- Static Website Hosting
- Cloud Architecture

## Lessons Learned

- Hosting websites using Amazon S3
- Configuring CloudFront for global content delivery
- Managing DNS with Route 53
- Implementing secure IAM permissions
- Troubleshooting AWS resource connectivity

## Outcome

Successfully deployed and secured a static website using AWS services, providing scalable hosting, fast global content delivery, and reliable DNS routing.
