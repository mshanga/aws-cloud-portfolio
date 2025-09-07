# AWS S3 Static Website Hosting

## 📌 Overview
This project demonstrates how to host a static website on **Amazon S3** with public access disabled, served securely via **CloudFront**.

## 🛠️ Architecture
- **S3 Bucket** for website files
- **CloudFront Distribution** for CDN
- **Route 53** for DNS mapping
- **ACM** for SSL certificate

![Architecture Diagram](architecture-diagram.png)

## 🚀 Steps
1. Create S3 bucket and enable static hosting.
2. Upload sample HTML/CSS website.
3. Configure CloudFront distribution with ACM SSL cert.
4. Point Route 53 DNS record to CloudFront.

## 🔐 Security
- Blocked public bucket access.
- Enabled CloudFront Origin Access Identity (OAI).
- Enforced HTTPS only.

## 📷 Screenshots
![S3 Setup](screenshots/s3-setup.png)

## ✅ Key Learnings
- Difference between S3 static hosting vs CloudFront.
- Cost optimization via CloudFront caching.
- Importance of security configs (OAI, HTTPS).
