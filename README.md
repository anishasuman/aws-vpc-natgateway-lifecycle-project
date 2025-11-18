# 🚀 AWS VPC + NAT Gateway + S3 Lifecycle Lab  
### Cloud Architecture & Implementation 

---

## 🌈 Animated Header Banner  
![AWS Cloud Banner](https://media.giphy.com/media/Q7SKqn3G97xpmfSOvG/giphy.gif)

---

## ⭐ Badges  
<p align="left">
  <img src="https://img.shields.io/badge/AWS-VPC-orange?style=for-the-badge&logo=amazon-aws" />
  <img src="https://img.shields.io/badge/AWS-EC2-blue?style=for-the-badge&logo=amazon-aws" />
  <img src="https://img.shields.io/badge/AWS-S3-green?style=for-the-badge&logo=amazon-s3" />
  <img src="https://img.shields.io/badge/NAT-Gateway-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
</p>

---

# 📌 Overview  

This repository contains two cloud tasks:

### ✔ **Task 1 – AWS VPC + NAT Gateway Networking**  
### ✔ **Task 2 – AWS S3 Lifecycle Rules Automation**


# 🏗 TASK 1 — AWS VPC & NAT GATEWAY SETUP

## ✔ Components Created  
- VPC (10.0.0.0/16)  
- Public Subnet (10.0.1.0/24)  
- Private Subnet (10.0.2.0/24)  
- Internet Gateway  
- NAT Gateway  
- Public Route Table → Internet Gateway  
- Private Route Table → NAT Gateway  
- EC2 (Public)  
- EC2 (Private)

---

## 🔥 Animated VPC Architecture  
![Architecture GIF](https://media.giphy.com/media/l0HlSNOxJB956qwfK/giphy.gif)

---

## 🧪 NAT Gateway Test (From Private EC2)

**Commands used:**
```bash
sudo dnf update -y
ping google.com
