## 📌 Overview

Hosting a static site on S3 is one of the simplest and most cost-effective ways to deploy static content such as HTML, CSS, JavaScript, and images.
This guide walks through all essential steps needed to make your website publicly accessible and secure.

## ✅ Steps Completed
- 1. Create and Configure S3 Bucket

Created a uniquely named S3 bucket.

Enabled Static Website Hosting in the bucket properties.

Uploaded all static website files (HTML, CSS, images, etc.).

<img width="2880" height="1504" alt="image" src="https://github.com/user-attachments/assets/67f87d6d-aaf8-402c-a278-2830631296e9" />


- 2. Set Permissions

Configured a bucket policy to allow public read access only to objects.

Ensured no unnecessary AWS resources or permissions were exposed.

<img width="2880" height="1502" alt="image" src="https://github.com/user-attachments/assets/81ca3e74-d995-4295-a674-b10ad12a1b2d" />


- 3. Website Configuration

Set index.html as the index document.

Set error.html as the error document (optional).

<img width="2880" height="1502" alt="image" src="https://github.com/user-attachments/assets/4ad41922-af00-423b-861d-9c60f11e6f59" />


- 4. Optional: DNS via Route 53

Connected a custom domain using Amazon Route 53 or another DNS provider.

Pointed the domain to the S3 website endpoint.

## 🎯 Final Results

Website is accessible using the S3 website endpoint or custom domain.

All website content (HTML, CSS, images) loads correctly.

Public access is restricted to read-only.

Setup follows AWS recommended security and scalability practices.

<img width="2880" height="1505" alt="image" src="https://github.com/user-attachments/assets/64eb6c88-1673-47a1-9ba7-5215ae70ab56" />


## 📚 Concepts Demonstrated

Creating and configuring an Amazon S3 bucket

Enabling static website hosting

Implementing secure S3 bucket policies

## 🔧 Requirements

AWS account with S3 access

Static website files ready to deploy

Basic DNS knowledge (if using custom domain)

Properly configured S3 public access settings


## 👤 Contact

Bhagvati Gaikwad
Pune, Maharashtra
