# Project-Implementation-Infrastructure-AWS-Console
The document outlines the implementation of a project using Amazon Web Services (AWS) Console. It details the creation of a custom Virtual Private Cloud (VPC) with public subnets, the launch of two EC2 Ubuntu server instances in separate availability zones, and the installation of Apache2 and nginx servers on these instances. 
# Project Requirements:
- Quick provision of two web servers on AWS with public access 
- Automate the servers provision on AWS using bash script
- Adhere to standard network security
- Ensure high availability

# Project-1 Task:
Using AWS services, create a custom VPC (Virtual private cloud) with public subnet. Launch two EC2 Ubuntu server instances. Each server should be in a separate availability zone. One server must host an Apache2 server while the other should launch a nginx server. Verify that both servers are running from a browser with the assigned public address. 

# Project Diagram:

![Image](https://github.com/user-attachments/assets/c269acd9-99bb-438c-a1bf-f15f7a32dd9e)

# Project Steps:

1. Create a VPC in AWS console with a total CIDR of 32bit. That is using 16bit for the VPC 10.0.0.0/16 and the rest 16bit for subnet. 
![Image](https://github.com/user-attachments/assets/87c3ec22-a4f4-4ec0-befe-754b81e80fe9)

2. Create Internet Gateway and attach it to VPC
![Image](https://github.com/user-attachments/assets/7f4b227a-5fe8-4303-aef2-4d760bb764e5)

