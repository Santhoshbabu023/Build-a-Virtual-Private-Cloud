# Build-a-Virtual-Private-Cloud

# AWS VPC Setup Project

This repository showcases the process of setting up an Amazon Virtual Private Cloud (VPC) with subnets, internet gateways, and public IP configurations using AWS. The objective is to help users understand how to isolate resources, control network traffic, and connect to the internet within AWS.

## Project Overview

In this project, the following steps were executed:
- Created a Virtual Private Cloud (VPC) in AWS.
- Set up subnets within the VPC, ensuring resources are organized by Availability Zones.
- Enabled auto-assign for public IPv4 addresses on subnets for easy access to internet-facing resources.
- Attached an internet gateway to allow public-facing instances to communicate with the internet.

## What You'll Learn
- How to create and configure a VPC in AWS.
- The difference between public and private subnets in a VPC.
- How to configure auto-assign IP addresses for public access.
- The role of an internet gateway in enabling internet connectivity for AWS resources.

## Steps Followed in This Project
1. **Create a VPC:** Configured a custom VPC to provide a secure, isolated network environment.
2. **Create Subnets:** Subnets were created in each Availability Zone to organize resources.
3. **Enable Public IP Assignment:** Auto-assigning public IPv4 addresses to the subnet to ensure EC2 instances are internet-accessible.
4. **Attach an Internet Gateway:** Attached an internet gateway to the VPC, ensuring internet access for resources in public subnets.

## Getting Started

To replicate this project in your own AWS account, follow these steps:

### Prerequisites
- An AWS account.
- Basic knowledge of AWS services (EC2, VPC, Subnets, etc.).

### Steps:
1. Navigate to the **VPC** section in your AWS Management Console.
2. Create a new VPC or use the default one.
3. Set up your subnets, ensuring the correct CIDR ranges for each subnet.
4. Enable auto-assign for public IP addresses in the subnet settings.
5. Create an internet gateway and attach it to the VPC.
6. Launch an EC2 instance in your public subnet to test the configuration.

## Conclusion
This project provides the foundational knowledge required to understand networking in AWS and the steps to configure a secure and isolated cloud environment. By following this project, you'll be equipped with the skills needed to build scalable, secure infrastructure for your applications in the cloud.

## Contributing

Feel free to fork this repository and contribute by opening an issue or a pull request with suggestions, improvements, or bug fixes.
