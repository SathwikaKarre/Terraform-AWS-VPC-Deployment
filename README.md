# Terraform-AWS-VPC-Deployment
This repository includes the Terraform code used to provision a secure AWS Virtual Private Cloud (VPC) with subnets, NACLs, and route tables. It also contains the deployment configuration for a sample application within the VPC, ensuring high availability, cost optimization, and secure infrastructure management.

This repository contains Terraform scripts for provisioning a complete AWS **Virtual Private Cloud (VPC)** along with subnets, **Network Access Control Lists (NACLs)**, route tables, and deployment of a sample application to ensure high availability, security, and cost optimization. This project demonstrates the use of Terraform to automate the setup of secure and scalable cloud infrastructure on AWS.

## **Project Overview**
This project provides an end-to-end solution for deploying a secure AWS infrastructure. It includes the creation of a VPC with public and private subnets, route tables, and security configurations, as well as the deployment of a sample application to demonstrate the functionality of the provisioned environment.

- **Terraform**: Automates the infrastructure provisioning.
- **AWS EC2**: Virtual servers to run your applications.
- **AWS VPC**: For creating isolated networks.
- **AWS NACLs**: Controls the flow of traffic at the subnet level.

Architecture of the AWS-VPC Deployment using Terraform:
![image](https://github.com/user-attachments/assets/4e4ed5b4-3780-4405-a7ac-6bd9dc019c56)



## **Technologies Used**
- **Terraform**: Infrastructure as code tool used to manage and provision AWS resources.
- **AWS VPC**: For network isolation and segmentation.
- **AWS EC2**: Virtual machines running applications within the VPC.
- **AWS NACLs**: To control network traffic in and out of subnets.

## **Key Features**
- **Automated Infrastructure Provisioning**: All AWS resources (VPC, subnets, EC2) are created via Terraform scripts.
- **Secure Network Configuration**: Public and private subnets, route tables, and NACLs ensure that resources are secure.
- **Cost Optimization**: Example application deployment in a cost-efficient manner within the VPC.

## **System Architecture**

AWS VPC -> Public Subnet -> EC2 Instance -> Sample Application -> Private Subnet -> EC2 Instance -> Sample Application

## **Setup Instructions**

### 1. **Clone the repository**
Clone the repository to your local machine or cloud environment.
bash
git clone https://github.com/<your-username>/Terraform-AWS-VPC-Deployment.git
cd Terraform-AWS-VPC-Deployment

## 2. Install Terraform

Download and install Terraform (version 0.12.x or higher) from here.

Install AWS CLI to configure your AWS credentials.


## 3. Configure AWS Credentials

1. Ensure you have AWS credentials configured on your local system:

      aws configure


2. Terraform will use these credentials to provision resources in AWS.



## 4. Initialize Terraform

Run the following command to initialize Terraform:

terraform init

## 5. Apply the Terraform Plan

To provision the AWS infrastructure, run the following command:

terraform apply

Review the execution plan, and type yes to proceed.


## 6. Verify Deployment

1. Log into your AWS Console.


2. Navigate to VPC and verify that your VPC, subnets, and route tables have been created.


3. Check EC2 to ensure that the sample application has been deployed successfully to the instances.



## How to Use

Modify the Terraform scripts to customize the VPC settings, instance types, and application configurations based on your needs.

The setup can be used as a template for creating custom cloud infrastructures with secure and scalable network configurations.


## Contributing

If you'd like to contribute to this project, follow these steps:

1. Fork the repository.


2. Create a feature branch.


3. Submit a pull request with a clear description of the changes.



## License

MIT License - See LICENSE for more information.

---

These detailed README.md files include all relevant information about setting up, using, and contributing to your projects. They explain the technologies used, step-by-step setup instructions, and provide a clear structure for others to follow. Feel free to tweak them according to your needs and make sure the instructions are easy to follow for anyone interested in using or contributing to your projects!
