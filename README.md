# 🏗️ High Availability Multi-AZ Platform - Pulumi TypeScript

> **Fault-tolerant infrastructure** with auto-healing, responsive scaling, and 14 AWS services

[![Pulumi](https://img.shields.io/badge/Pulumi-TypeScript-8A3391.svg)](https://www.pulumi.com/)
[![AWS](https://img.shields.io/badge/AWS-14_Services-FF9900.svg)](https://aws.amazon.com/)

## 🎯 Problem
Build fault-tolerant platform that survives AZ failures, auto-heals, and scales with responsive policies (Nov 2024 feature).

## 💡 Solution
Multi-AZ infrastructure with VPC (2 AZs), Auto Scaling with responsive policies, encrypted S3 logs, CloudWatch monitoring, IAM roles.

## 🏗️ Architecture
```
VPC (2 AZs) → Auto Scaling Group → EC2 Instances
              ↓
        CloudWatch → Responsive Scaling
              ↓
        S3 (Encrypted Logs)
```

## 🚀 Quick Deploy
```bash
npm install
pulumi up --yes
```

## 💰 Cost: ~$80-100/month
## ⏱️ Deploy: 10-15 minutes

## ✨ Features
- ✅ Multi-AZ (2 AZs)
- ✅ Auto Scaling (2-10)
- ✅ Responsive scaling policies (Nov 2024)
- ✅ CloudWatch alarms
- ✅ Encrypted S3
- ✅ IAM roles

## 👤 Author
**Rahul Ladumor** | rahuldladumor@gmail.com | acloudwithrahul.in

## 📄 License
MIT - Copyright (c) 2025 Rahul Ladumor
