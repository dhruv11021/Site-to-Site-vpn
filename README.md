# Site-to-Site VPN using AWS

This project sets up a Site-to-Site VPN connection using AWS Virtual Private Gateway and Customer Gateway to securely connect on-premises networks with AWS infrastructure.

## 📘 Overview

- 🌐 Two VPCs or one VPC and a local network are connected via VPN.
- 🔐 IPsec tunnels for secure communication.
- ⚙️ AWS services used:
  - VPC
  - Virtual Private Gateway
  - Customer Gateway
  - Route Tables
  - VPN Connection

## 🧰 Tools Used

- AWS Management Console
- Network diagram 
## 📌 Setup Steps

1. Create a VPC in AWS.
2. Create a Virtual Private Gateway and attach it to the VPC.
3. Create a Customer Gateway with your public IP or a simulation.
4. Create a VPN connection using both the gateways.
5. Update route tables for proper traffic routing.
6. (Optional) Test connectivity via EC2 instances in the VPC.


##🔒 This project demonstrates a secure and scalable Site-to-Site VPN setup on AWS, ideal for extending on-premises infrastructure to the cloud.
