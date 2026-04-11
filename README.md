# ☁️ AWS Scalable E-commerce Architecture (Capstone Project)

## 📌 Overview
This project presents a scalable and highly available cloud architecture for an e-commerce platform built using AWS services. It is designed to handle global traffic, ensure fault tolerance, and provide secure and efficient data management.

---

## 🏗️ Architecture Breakdown

### 🌐 User Layer
Users access the platform via web or mobile applications through a domain name.

### 🌍 DNS & Routing
- Amazon Route 53 handles domain resolution and traffic routing.
- Health checks ensure high availability.

### 🚀 Content Delivery
- Amazon S3 hosts static assets (HTML, CSS, images).
- CloudFront delivers content globally with low latency.

### 🔐 Security Layer
- AWS WAF protects against common attacks (SQL injection, DDoS).

### ⚖️ Load Balancing
- Application Load Balancer distributes traffic across servers.

### 🖥️ Compute Layer
- EC2 instances run application logic.
- Auto Scaling ensures performance under varying loads.

### 🗄️ Data Layer
- Amazon RDS/Aurora for relational data.
- DynamoDB for fast NoSQL storage.

### 📊 Monitoring
- CloudWatch monitors system performance and health.

---

## 🚀 Key Features
- High availability across multiple zones  
- Auto-scaling infrastructure  
- Global content delivery  
- Secure and resilient architecture  
- Cost optimization strategies  

---

## 🛠️ Technologies Used
- AWS (EC2, S3, RDS, DynamoDB, CloudFront, Route 53, WAF)
- Cloud Architecture Design(Lucid chart)

---

## 📄 Project Document
See full documentation here:  
([Full document]GOODNESS_ADEPOJU  AWS SAA CAPSTONE PROJECT.docx
[architecture diagram]IMG_20260411_004349.jpg)

---

## 👨‍💻 Author
Adepoju Goodness Taiwo  
GitHub: https://github.com/Goodness4life
