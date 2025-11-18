# 🚀 AWS VPC + NAT Gateway + S3 Lifecycle Lab  
### Cloud Architecture & Implementation  


## 🌈 **Animated Header Banner**
![AWS Cloud Banner](https://media.giphy.com/media/Q7SKqn3G97xpmfSOvG/giphy.gif)

---

## ⭐ **Badges**
<p align="left">
  <img src="https://img.shields.io/badge/AWS-VPC-orange?style=for-the-badge&logo=amazon-aws" />
  <img src="https://img.shields.io/badge/AWS-EC2-blue?style=for-the-badge&logo=amazon-aws" />
  <img src="https://img.shields.io/badge/AWS-S3-green?style=for-the-badge&logo=amazon-s3" />
  <img src="https://img.shields.io/badge/NAT-Gateway-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
</p>

---

# 📌 Overview  

This repository contains **Task 1 (VPC + NAT)** and **Task 2 (S3 Lifecycle Rules)** from the Cloud Architecture CA1.

---

# 🏗 **Task 1 — AWS VPC Networking**

### ✔ Components Created
- VPC (10.0.0.0/16)  
- Public Subnet (10.0.1.0/24)  
- Private Subnet (10.0.2.0/24)  
- Internet Gateway  
- NAT Gateway  
- Public Route Table (0.0.0.0/0 → IGW)  
- Private Route Table (0.0.0.0/0 → NAT Gateway)  
- EC2 in Public Subnet  
- EC2 in Private Subnet  

---

## 🔥 Animated VPC Architecture (GIF)
![Architecture GIF](https://media.giphy.com/media/l0HlSNOxJB956qwfK/giphy.gif)

---

## 🧪 Private EC2 Internet Test (NAT Gateway)

**Commands used:**
```bash
sudo dnf update -y
ping google.com
