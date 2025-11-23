Static Website Hosting on Amazon S3

This project demonstrates how to host a static website using Amazon S3. It covers bucket setup, static hosting configuration, access permissions, and optional DNS routing via Route 53.

Steps Completed
1. S3 Bucket Setup

Created an S3 bucket with a unique name.

Enabled Static Website Hosting from the bucket properties.

Uploaded all required website files (HTML, CSS, images).

2. Access and Permissions

Configured a bucket policy allowing public read access to objects only.

Ensured no unnecessary AWS services or permissions were exposed.

3. Website Configuration

Set index.html as the index document.

Set error.html as the error document (optional).

4. Optional DNS Configuration

Configured Route 53 or another DNS provider to point a custom domain to the S3 website endpoint.

Results

Website is accessible via the S3 website endpoint or a custom domain.

All website content loads correctly.

Public access is limited to object-level read permissions only.

Demonstrates secure and scalable static website hosting using Amazon S3.

Screenshots (Optional)

Recommended screenshots for documentation:

S3 bucket creation screen

Static website hosting configuration panel

Bucket policy editor showing public access JSON

Website loaded in a web browser via the S3 endpoint

Concepts Demonstrated

Amazon S3 bucket creation and configuration

Using S3 Static Website Hosting

Bucket policies and public access control

DNS configuration with Route 53 or other providers

AWS security and scalability best practices

Example Project Structure
s3-static-website-hosting/
│
├─ index.html
├─ styles.css
├─ images/
│   └─ logo.png
└─ README.md

Requirements

AWS account with S3 permissions

Static website files ready for upload

Basic understanding of DNS if using a custom domain

Careful configuration of bucket policies for public access

License

Add your preferred open-source license here.

Contact

Bhagvati Gaikwad
Pune, Maharashtra
