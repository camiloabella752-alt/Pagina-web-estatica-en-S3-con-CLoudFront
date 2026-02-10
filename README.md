# AWS Static Website with CloudFront

## 📌 Project Overview
This project demonstrates how to deploy a low-cost, secure, and scalable static website on AWS using Amazon S3 and Amazon CloudFront.

The main goal is to showcase core AWS fundamentals such as storage, content delivery, security, and cost optimization.

---

## 🧱 Architecture
User → CloudFront (HTTPS) → Amazon S3 (Static Website)

---

## 🛠️ AWS Services Used
- Amazon S3 (Static website hosting)
- Amazon CloudFront (CDN & HTTPS)
- IAM (Access control)

---

## 🚀 Deployment Steps
1. Created an S3 bucket to store static website files.
2. Enabled Static Website Hosting and configured the index document.
3. Configured public read access using a bucket policy.
4. Created a CloudFront distribution with HTTPS redirection.
5. Set CloudFront as the secure entry point for the website.

---

## 🔐 Security Considerations
- HTTPS enforced using CloudFront.
- S3 bucket access controlled via policies.
- No EC2 or servers exposed (serverless architecture).

---

## 💰 Cost Optimization
- Fully covered by AWS Free Tier.
- No always-on compute resources.
- Pay-per-use model.

---

## 📚 Key Learnings
- Hosting static websites using Amazon S3.
- Using CloudFront as a CDN for performance and security.
- Understanding IAM policies and public access controls.
- Designing low-cost cloud architectures.

---


