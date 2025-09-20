# AWS-VPC-Peering-and-Security-Project
This project demonstrates a secure and scalable infrastructure design on AWS, utilizing VPC peering, Bastion Hosts, Route Tables, and Security Groups to enable efficient and secure communication between isolated networks.

## Overview
This project showcases a secure AWS infrastructure design, featuring VPC peering, Bastion Hosts, and network security best practices. The goal is to enable efficient and secure communication between isolated networks while maintaining top-notch security.

## Project Highlights
* Established a peering connection between two VPCs
* Set up a highly secure Bastion Host in a public subnet
* Configured Route Tables to route traffic between VPCs
* Implemented Security Groups to allow ICMP traffic between private instances

## Architecture
The project architecture consists of two VPCs, each with a public and private subnet. A Bastion Host is set up in the public subnet of one VPC, allowing secure access to private instances.

## Components
* VPC Peering
* Bastion Host
* Route Tables
* Security Groups

## Setup and Configuration
To set up this project, follow these steps:

1. Create two VPCs with public and private subnets
2. Establish a peering connection between the VPCs
3. Set up a Bastion Host in the public subnet of one VPC
4. Configure Route Tables to route traffic between VPCs
5. Implement Security Groups to allow ICMP traffic between private instances

## Testing and Validation
The project includes testing and validation scripts to verify the setup and configuration. Run the following commands to test the connectivity between private instances:

* SSH into a private instance in one VPC from the Bastion Host
* Run a ping command to test connectivity between private instances in both VPCs

## Lessons Learned
This project taught me the importance of secure network architecture in cloud computing and how to design and implement a scalable and secure infrastructure using AWS services.

## Project Snapshots
### VPC Creation

<img width="1626" height="267" alt="image" src="https://github.com/user-attachments/assets/f5ce2495-aeec-4eb8-a063-7f3b9e56c04e" />





### Private Instances and Bastion Host


<img width="1888" height="816" alt="image" src="https://github.com/user-attachments/assets/60c0fb22-c341-4648-878e-6e2ca450abdb" />





### Peering Connection between VPCs

<img width="1893" height="559" alt="image" src="https://github.com/user-attachments/assets/a7d1d266-b3c4-45ad-a9d7-1eb36da636a4" />





### Ping Connection


<img width="1920" height="1021" alt="image" src="https://github.com/user-attachments/assets/e5db91b8-7a83-4fd9-a169-0beb9ac219a5" />



