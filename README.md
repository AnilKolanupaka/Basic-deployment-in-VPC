# 🚀 Basic Deployment in VPC (AWS EC2 Frontend Project)

## 📌 Project Overview
This project demonstrates a basic frontend deployment on an AWS EC2 instance inside a custom VPC. The application is hosted using Nginx and is accessible via a public IP through an Internet Gateway.

---

## 🏗️ Architecture
- Custom VPC (10.0.0.0/16)
- Public Subnet (10.0.1.0/24)
- Internet Gateway attached to VPC
- Route Table configured for internet access
- EC2 instance deployed in public subnet
- Security Group allowing HTTP (80) and SSH (22)

---

## ⚙️ Tech Stack
- AWS EC2
- AWS VPC
- Linux (Amazon Linux / Ubuntu)
- Nginx Web Server
- HTML, CSS, JavaScript

---

## 🚀 Deployment Steps
1. Created VPC with public subnet
2. Attached Internet Gateway
3. Configured Route Table
4. Launched EC2 instance in public subnet
5. Installed Nginx on EC2
6. Deployed static frontend (index.html)
7. Accessed via public IP

---

## 🌐 How to Run
Open browser and hit:

http://<EC2-PUBLIC-IP>

---

## 📸 Features
- Simple cloud dashboard UI
- Deployed inside AWS VPC
- Public accessibility using Internet Gateway
- Lightweight static frontend

---

## 📚 Learning Outcome
- AWS VPC networking basics
- EC2 instance deployment
- Security group configuration
- Linux server setup
- Static web hosting using Nginx

---

## 👨‍💻 Author
Anil Chari
AWS Cloud Engineer (Learning Project)

---

## 📌 Note
This is a beginner-level AWS project to understand VPC + EC2 + web hosting basics.
