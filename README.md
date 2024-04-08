# AWS 2-tier architecture Migration Project for Company ABC

## Introduction

Amazon Elastic Compute Cloud (Amazon EC2) offers scalable computing capacity within the Amazon Web Services (AWS) cloud environment. By leveraging EC2, companies like Company ABC can streamline their development and deployment processes, eliminating the need for upfront hardware investments. With EC2, users can easily launch and manage virtual servers, configure security settings, and handle storage efficiently. Moreover, EC2's scalability feature enables seamless adjustments to meet changing workload demands, reducing the necessity for traffic forecasting.

## Problem Statement

Company ABC intends to migrate their product to AWS. Currently, they have a MySQL database and a PHP-based website in place. The company aims to ensure high availability for their product, necessitating the implementation of Auto Scaling on their website.

## Steps to Solve

1. **Launch an EC2 Instance**: Provision an EC2 instance to host the PHP website.

2. **Enable Auto Scaling on EC2 Instances**: Configure Auto Scaling to dynamically adjust the number of EC2 instances based on demand, ensuring high availability.

3. **Create an RDS Instance**: Deploy a MySQL database using Amazon RDS to securely store the product's data.

4. **Create Database & Table in RDS Instance**:
    - **Database Name**: intel
    - **Table Name**: data
    - **Database Password**: inte1123

5. **Change Hostname in Website**: Update the website's configuration to connect to the RDS instance using the appropriate hostname.

6. **Allow Traffic from EC2 to RDS Instance**: Configure security group settings to permit traffic from EC2 instances to the RDS instance.

7. **Allow All-Traffic to EC2 Instance**: Adjust security group settings to allow inbound traffic to the EC2 instance as necessary.

## Conclusion

By following these steps, Company ABC can effectively migrate their product to AWS, achieving high availability through Auto Scaling and leveraging Amazon RDS for database management. This migration ensures scalability, reliability, and efficient resource management, empowering the company to focus on innovation and growth.
