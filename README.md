# 🌐  Static Website Hosting on AWS

This project demonstrates how to **host a static website on AWS** using **Amazon S3** and **Amazon CloudFront** for fast, secure, and scalable content delivery.  
It is part of the *Accenture Primers Project Task* focused on deploying and distributing static web content efficiently through AWS cloud services.

---

## 🧾 Project Summary

The goal of this project is to deploy a **static website** (HTML, CSS, and JavaScript files) to the AWS Cloud.  
The process involves:

1. Creating and configuring an **S3 bucket** for website hosting.  
2. Uploading all website files (HTML, CSS, JS, images) to the bucket.  
3. Securing access with appropriate **IAM policies**.  
4. Speeding up global content delivery using **AWS CloudFront**.  
5. Verifying website accessibility through both **S3 Endpoint** and **CloudFront Distribution URL**.

This project highlights the ability to use **cloud infrastructure for web hosting**, ensuring low latency, scalability, and reliability.

---

## ☁️ AWS Services Used

- **Amazon S3** – For static website hosting.  
- **Amazon CloudFront** – For content delivery and caching.  
- **IAM** – For managing user access and permissions.   

---

## 🌍 Deployed URLs

- **S3 Website Endpoint:**  
  🔗 [http://my-4125-7023-6352-bucket.s3-website-us-east-1.amazonaws.com](http://my-4125-7023-6352-bucket.s3-website-us-east-1.amazonaws.com)

- **CloudFront Distribution URL:**  
  🔗 [http://d2p9og5esonrzt.cloudfront.net](http://d2p9og5esonrzt.cloudfront.net)

Click the above links to directly view the hosted website.

---

## 🪜 Steps Followed

### 1️⃣ Create S3 Bucket and Enable Static Website Hosting
- Created an S3 bucket named `my-4125-7023-6352-bucket`.
- Enabled **Static Website Hosting** in bucket properties.
- Configured **index.html** as the root file.
- Updated **bucket policy** to allow public read access for website content.

### 2️⃣ Upload Website Files
- Uploaded all HTML, CSS, and image files to the bucket.
- Verified file permissions and accessibility.

### 3️⃣ Configure CloudFront Distribution
- Created a new CloudFront distribution.
- Set the **Origin Domain Name** as the S3 static website endpoint.
- Selected **Redirect HTTP to HTTPS** to ensure secure delivery.
- Waited for deployment until status changed to **“Deployed.”**

### 4️⃣ Verify Website Accessibility
- Tested website accessibility via both the S3 and CloudFront URLs.
- Confirmed successful rendering of web pages.
- Captured screenshots of each verification step.

---

## 🖼️ Screenshots

All setup and verification screenshots are included in the following folders:

- 📁 `Website Files`
- 📁 `Website Distribution`
- 📁 `Web Browser Access`

Each folder contains images showcasing the configuration and results of the respective steps.

---

## 🧠 Key Learnings

- How to host and configure static websites using AWS S3.  
- How to distribute website content globally using CloudFront.  
- Understanding of IAM roles, policies, and bucket permissions.  
- Practical exposure to AWS web hosting workflow.

---

## 🏁 Conclusion

This project successfully demonstrates the end-to-end deployment of a static website on AWS infrastructure.  
By integrating **Amazon S3** and **CloudFront**, the website achieves **fast content delivery**, **scalability**, and **high availability**, which are essential for modern cloud-based web applications.

---

## Regards
Anjana E.
---
⭐ *Deployed as part of the Accenture Primers Cloud Project on Static Website Hosting using AWS.*
