# Windows EC2 Web Server Deployment on AWS

## Project Overview
A Windows-based web server deployment project using Amazon EC2 and IIS. The project demonstrates AWS networking, secure server access, web server configuration, and S3 backup.

## AWS Services Used
- Amazon EC2
- Amazon VPC
- Internet Gateway
- Route Table
- Security Groups
- Amazon S3
- AWS Systems Manager
- AWS IAM
- Amazon CloudWatch

## Architecture
Internet → Internet Gateway → Public Subnet → Windows EC2 → IIS Web Server

## Key Features
- Created a custom VPC with a public subnet
- Configured Internet Gateway and route table
- Deployed Windows Server on EC2
- Configured Security Group rules
- Connected to EC2 using AWS Systems Manager Session Manager
- Installed and configured IIS Web Server
- Hosted a web page using IIS
- Configured Amazon S3 for backup and versioning
- Applied IAM-based access control

## Technologies
AWS Cloud | EC2 | VPC | Windows Server | IIS | S3 | IAM | Systems Manager | CloudWatch

## Project Outcome
Successfully deployed and accessed a Windows IIS Web Server on AWS EC2 through the public internet while implementing secure networking and cloud-based backup.
