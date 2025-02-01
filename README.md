# Student Survey Form on AWS 🚀

This project consists of:
- **Static Homepage** hosted on **AWS S3**
- **Student Survey Form** hosted on an **AWS EC2 instance**

## 🌐 Live Links

- **Homepage (AWS S3):** [http://your-s3-website-url](http://your-s3-website-url)
- **Survey Form (AWS EC2):** [http://your-ec2-public-ip/survey.html](http://your-ec2-public-ip/survey.html)

## 📌 Project Overview

### **Part 1: Hosting Static Homepage on AWS S3**
- Created an `index.html` homepage and uploaded it to an **S3 bucket**.
- Enabled **public access** and set up **static website hosting**.
- Configured **error.html** as a fallback page.

### **Part 2: Deploying  Survey on AWS EC2**
- Launched an **EC2 instance** (Amazon Linux 2).
- Installed **Apache** to serve the survey form.
- Created a **survey.html** form with fields like name, email, checkboxes, and a submit button.
- Linked `survey.html` from `index.html` on the **S3 homepage**.
- Created `thankyou.html` to acknowledge form submissions.
