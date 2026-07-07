# AWS Static Website Deployment with CloudFront CDN

An automated and secure cloud infrastructure project demonstrating high-availability static web hosting on AWS.

## 🚀 Live Demo
You can access the secure live website here: 
👉 **[Live Website Link](https://da8c0xrsf6y00.cloudfront.net)**

## 🛠️ Architecture & Tech Stack
* **Amazon S3**: Hosted static web files (`index.html`) with highly durable storage.
* **Amazon CloudFront**: Configured as a Content Delivery Network (CDN) to cache content at edge locations for low latency.
* **AWS IAM & OAC**: Secured the S3 bucket by restricting direct public access, allowing only CloudFront to read via Origin Access Control.
* **HTTPS/SSL**: Enabled secure communication protocols automatically through CloudFront distribution.

## 📈 Key Learnings
* Setting up CloudFront Distributions and managing Origin Access Control (OAC).
* Securing cloud storage buckets using minimum-privilege IAM and Bucket Policies.
* Creating production-ready documentation for cloud architectures.
*