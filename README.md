# 🌐 AWS S3 Static Website Hosting
## 📋 Project Overview
Hosted a static personal portfolio website on Amazon S3 with public 
access bucket policy. Tested CloudFront CDN integration 
(restricted in Vocareum lab environment).

---

## 🏗️ Architecture
```
User Browser
     ↓
Amazon S3 Static Website Endpoint
     ↓
index.html served directly
```

---

## ⚙️ AWS Services Used
| Service | Purpose |
|---------|---------|
| Amazon S3 | Stores and serves website files |
| S3 Static Hosting | Serves HTML as a website |
| Bucket Policy | Allows public read access |
| Amazon CloudFront | CDN (restricted in lab) |

---

## 🛠️ Steps Completed
1. Created S3 bucket — rokit-static-website
2. Disabled Block Public Access
3. Uploaded index.html website file
4. Enabled Static Website Hosting
5. Added public Bucket Policy
6. Tested website via S3 endpoint URL ✅

---

## 🌍 Live Website
Hosted via S3 static website endpoint:
`http://rokit-static-website.s3-website-us-west-2.amazonaws.com`

---

## ✅ What I Demonstrated
- ✅ S3 Object Storage
- ✅ Static Website Hosting
- ✅ Bucket Policy (JSON IAM)
- ✅ Public Access Configuration
- ✅ CloudFront CDN concepts

---

## 🧪 Lab Environment
- Platform: Vocareum AWS Sandbox
- Region: us-west-2 (Oregon)

---

## 👨‍💻 Author
///**rokit-cloud**\\\
