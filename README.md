# 🚀 AWS EC2 Instance Launch

A beginner-friendly AWS Cloud Computing project that demonstrates how to launch, configure, and access an Amazon EC2 (Elastic Compute Cloud) instance using the AWS Management Console.

---

## 📌 Project Description

This project explains the complete process of creating an EC2 virtual server on AWS. It covers selecting an Amazon Machine Image (AMI), choosing an instance type, configuring networking and security settings, creating a key pair, launching the instance, and connecting to it securely.

---

## 🎯 Objective

- Understand the basics of Amazon EC2.
- Learn how to launch a virtual machine in AWS.
- Configure networking and security settings.
- Connect to the instance securely.
- Explore the EC2 instance lifecycle.

---

## ☁️ AWS Services Used

- Amazon EC2
- Amazon VPC
- Security Groups
- Key Pair
- EC2 Instance Connect / SSH

---

## 🛠️ Tools & Technologies

- AWS Management Console
- Amazon Linux 2023 AMI
- EC2 Instance Connect / SSH
- Web Browser

---

## 📋 Prerequisites

Before starting this project, ensure you have:

- An AWS Account
- Internet Connection
- Basic understanding of Cloud Computing
- Modern Web Browser

---

# 📖 Implementation Steps

### Step 1: Login to AWS
- Logged in to the AWS Management Console.

### Step 2: Open EC2 Dashboard
- Navigated to **Services → EC2**.

### Step 3: Launch Instance
- Clicked **Launch Instance**.

### Step 4: Configure Instance
- Entered the instance name.
- Selected **Amazon Linux 2023 AMI**.
- Chose **t2.micro** (Free Tier Eligible).

### Step 5: Create Key Pair
- Created a new Key Pair.
- Downloaded the `.pem` file securely.

### Step 6: Configure Network
- Selected the default VPC.
- Allowed inbound traffic for:
  - SSH (Port 22)
  - HTTP (Port 80)
  - HTTPS (Port 443)

### Step 7: Review & Launch
- Reviewed all configuration settings.
- Clicked **Launch Instance**.

### Step 8: Verify Instance
- Confirmed the instance entered the **Running** state.
- Verified that all status checks passed.

### Step 9: Connect to EC2
- Connected using **EC2 Instance Connect** or **SSH**.
- Successfully accessed the Linux terminal.

### Step 10: Monitor Instance
- Viewed:
  - Instance ID
  - Public IPv4 Address
  - Private IPv4 Address
  - Availability Zone
  - Instance State

### Step 11: Stop & Restart
- Stopped the instance.
- Restarted the instance successfully.

### Step 12: Terminate Instance
- Terminated the instance after completing the project to avoid unnecessary AWS charges.

---

# 📂 Project Structure

```
AWS-EC2-Instance-Launch/
│
├── README.md
├── screenshots/
│   ├── 01-login.png
│   ├── 02-ec2-dashboard.png
│   ├── 03-launch-instance.png
│   ├── 04-select-ami.png
│   ├── 05-instance-type.png
│   ├── 06-key-pair.png
│   ├── 07-security-group.png
│   ├── 08-review.png
│   ├── 09-running-instance.png
│   └── 10-connection.png
│
└── LICENSE
```

---

# 📷 Screenshots

Include screenshots for each major step:

- AWS Console
- EC2 Dashboard
- Launch Instance Page
- AMI Selection
- Instance Type Selection
- Key Pair Creation
- Security Group Configuration
- Running Instance
- EC2 Connection
- Linux Terminal

---

# 🎓 Learning Outcomes

After completing this project, I learned:

- Introduction to Amazon EC2
- How virtual machines work in AWS
- Importance of Amazon Machine Images (AMI)
- Instance type selection
- Security Groups and firewall rules
- Key Pair authentication
- EC2 networking basics
- Connecting to Linux servers
- EC2 instance lifecycle
- Cloud infrastructure fundamentals

---

# 🌟 Key Features

- AWS Free Tier Compatible
- Beginner Friendly
- Secure Remote Access
- Virtual Server Deployment
- Basic Cloud Infrastructure Setup

---

# 🔒 Security Considerations

- Keep the `.pem` key secure.
- Do not expose private keys publicly.
- Restrict inbound rules to required ports only.
- Terminate unused instances to avoid unexpected charges.

---

# 📚 References

- AWS Documentation
- Amazon EC2 User Guide
- AWS Free Tier Documentation

---

# 👩‍💻 Author

**Kartiki Mane**

Computer Science Engineering Student

Passionate about Cloud Computing, AWS, Python, and Software Development.

---

