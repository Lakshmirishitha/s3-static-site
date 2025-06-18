# Create a README.md content for GitHub
readme_content = """
# 🚀 Scalable Static Website Deployment with AWS S3 + GitHub Actions + Custom Domain

## 📌 Project Overview
This project demonstrates the end-to-end DevOps workflow to host and automate deployment of a static website using AWS S3, GitHub Actions, and a custom domain via InfinityFree.

## 🌐 Live Website
[www.rishitha.rf.gd](http://www.rishitha.rf.gd)

## 🛠️ Tools & Technologies
- AWS S3 (Static Website Hosting)
- GitHub & GitHub Actions (CI/CD Pipeline)
- AWS IAM (Secure Access Keys)
- InfinityFree (Free Domain & DNS Management)
- HTML/CSS (Static Site)
- DNS (CNAME Records)

## 🧩 Key Features
- Automatic deployment on GitHub push
- Serverless hosting on AWS S3
- Secure deployment using IAM user credentials
- Public access + custom domain routing with DNS
- Easy and scalable cloud website hosting

## 📦 How It Works
1. Created a static HTML website (`index.html`)
2. Hosted the site using AWS S3 with public access and static hosting enabled
3. Set up a GitHub repository with `.github/workflows/deploy.yml`
4. Created an IAM user and configured `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` as GitHub Secrets
5. Integrated a custom domain (`www.rishitha.rf.gd`) via InfinityFree using a CNAME record
6. On each GitHub push, the workflow deploys the latest version to S3 automatically

## 🔒 Security
- IAM user created with AmazonS3FullAccess policy
- GitHub Secrets used for securely storing AWS credentials

## ✅ Outcome
Successfully built and deployed a live static website with automated deployment and custom domain, reflecting real-world DevOps skills.

## 📷 Screenshots
- GitHub Actions CI/CD Workflow
- AWS S3 Static Website Settings
- IAM User Creation
- Live Custom Domain
- S3 Bucket Contents

## 🙋‍♀️ Developed by
**Jinka Lakshmi Rishitha**
"""


