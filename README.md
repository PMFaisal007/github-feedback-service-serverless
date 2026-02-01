# Serverless Feedback Collection System (AWS)

A real-world serverless web application built on AWS that allows users to submit feedback along with PDF uploads.

## 🔗 Live Demo
https://feedback.publicvm.com

## 🏗️ Architecture
User → CloudFront → S3 (Private)  
Form Submission → API Gateway → Lambda  
Data → DynamoDB  
PDF → S3  
Notification → SES

## 🛠️ Tech Stack
- Amazon S3 (Private)
- Amazon CloudFront
- API Gateway
- AWS Lambda
- DynamoDB
- Amazon SES
- GitHub Actions (CI/CD)

## ✨ Features
- Secure static website hosting
- Serverless backend processing
- PDF upload support
- Email notifications
- Automated frontend deployment

## 🚀 CI/CD
Frontend is automatically deployed to S3 using GitHub Actions on every push.

## 📌 What I Learned
- Designing serverless AWS architectures
- Handling file uploads without servers
- Secure frontend delivery using CloudFront
- CI/CD automation with GitHub Actions

## 📸 Architecture Diagram
![Architecture](infrastructure/architecture.png)
