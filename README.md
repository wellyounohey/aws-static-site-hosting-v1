# 🖥️ Static Website Hosting on AWS (S3 + CloudFront + Route 53)

This project demonstrates how to host a static website using **Amazon S3**, with optional distribution through **CloudFront** and domain routing via **Route 53**. It was built as part of a hands-on AWS learning journey, following best practices in cloud architecture and deployment.

---

## 📁 Project Structure
---

## 🚀 Features

- ✅ Static website hosting using **Amazon S3**
- ✅ Public access configuration for browser access
- ✅ (Optional) **CloudFront CDN** setup for fast global delivery
- ✅ (Optional) Custom domain with **Route 53**
- ✅ Clean project structure with Git version control

---

## 🌐 Live Demo

👉 [View Website on S3](https://aws-static-site-cardinalblue.s3.us-east-1.amazonaws.com/index.html)

---

## 🧰 Technologies Used

- **Amazon S3** – Static file storage and website hosting
- **AWS IAM** – Secure access setup via roles and policies
- **(Optional) CloudFront** – Content Delivery Network (CDN)
- **(Optional) Route 53** – Domain registration and DNS routing
- **Git & GitHub** – Version control and collaboration

---

## 🗺️ Architecture Overview

If included, the `diagram.png` shows a visual overview of the hosting architecture:

---

## 🛠️ How to Deploy

1. **Upload files to S3 bucket**
2. Enable static website hosting in bucket properties
3. Set proper **bucket policy** for public access
4. (Optional) Set up CloudFront and Route 53
5. Test public URL: `https://<your-bucket-name>.s3.<region>.amazonaws.com/index.html`

---

## 📌 Author Notes

This project is part of my AWS Solution Architect learning journey, built while following [Adrian Cantrill's AWS course](https://learn.cantrill.io). The focus is on **hands-on experience** and real-world cloud architecture.

---

## 📎 License

This project is for educational purposes. Feel free to fork and use it as a base for your own deployments.





