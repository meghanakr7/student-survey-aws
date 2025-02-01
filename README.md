# Student Survey Form on AWS 🚀

This project consists of:
- **Static Homepage** hosted on **AWS S3**
- **Student Survey Form** hosted on an **AWS EC2 instance**

## 🌐 Live Links

- **Homepage (AWS S3):** [http://my-swe645-class-homepage.s3-website.us-east-2.amazonaws.com/](http://my-swe645-class-homepage.s3-website.us-east-2.amazonaws.com/)
- **Survey Form (AWS EC2):** [http://3.147.103.164/survey.html](http://3.147.103.164/survey.html)

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
