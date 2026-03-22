
# 🔐 Cloud Security with AWS IAM

## 📌 Project Overview
This project demonstrates how to secure AWS resources using IAM.

## 🎯 Objective
Control access to EC2 instances using IAM policies and tags.

## 🧱 Architecture
- EC2 Production Instance (Env: Production)
- EC2 Development Instance (Env: Development)
- IAM Policy restricting access to Development only

## ⚙️ Steps Performed
1. Created EC2 instances (Dev & Prod)
2. Tagged instances using Env key
3. Created IAM Policy with conditions
4. Created IAM User Group
5. Assigned policy to group
6. Created IAM User and added to group
7. Tested access restrictions

## 🔐 Security Concept
- Principle of Least Privilege
- Tag-based access control
- Role-based access

## 📸 Screenshots
(Add images here)

## 🚀 Result
User can access only development resources, not production.

## 🛠 Tools Used
- AWS IAM
- AWS EC2