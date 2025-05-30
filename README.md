# AWS_Certified_DataEngineer_Associate_hands-on-practice

# Introduction
This github acts as a resource for the AWS Certified Data Engineer - Associate (DEA-C01) certfication exam. The repo contains the code alongside a detailed README that gives definitions of teh AWS services and other areas of knowledge required for the certification.


# Setup
The set-code.yaml contains code to be executed using Amazon CloudFormation. The code creates the base networking artefacts and S3 Bucket required to complete the remaining sections of the course. The S3 Bucket will require a name which is globally unique to AWS to be entered before executing the stack.

The following artefacts are created by the code;

- VPC
- Two public Subnets
- Security Groups
- Routing Table
- S3 Bucket
After the code has been executed the following steps need to be executed on the console.

1. Create a rawData data folder in the S3 bucket.
2. Create a processedData folder in the S3 bucket.
3. Create a scriptLocation folder in the S3 bucket.
4. Create a tmpDir folder in the S3 bucket.
5. Create a athena folder in the S3 bucket.
Upload source data into the rawData folder maintaining folder structure of customers, employees, and orders, .

The S3 bucket should have the follow structure once set up;

<img width="781" alt="image" src="https://github.com/user-attachments/assets/a2090406-6fa6-4e05-a26c-159059419fd1" />
