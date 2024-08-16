🛠️ AWS Transit Gateway Topology with VPCs, Security Groups, and NACLs
This repository showcases a practical implementation of an advanced AWS network architecture. The project involves creating three VPCs, each with two subnets, and connecting them via a Transit Gateway. Additionally, custom Security Groups and Network ACLs are configured to secure SSH and ICMP traffic, enabling secure communication between the VPCs.

![AWS Transit Gateway Topology](topology.png)

🎯 Project Overview
VPC Creation: Set up three VPCs (VPC1, VPC2, VPC3) with subnets across different availability zones.
Transit Gateway: Establish a Transit Gateway to connect the VPCs for seamless communication.
Security Configuration: Implement custom Security Groups and Network ACLs to allow SSH (port 22) and ICMP (ping) traffic between VPCs.
Testing: Launch EC2 instances and validate inter-VPC connectivity for SSH and ping.
📄 Documentation
Detailed step-by-step documentation is available here to guide you through the entire setup process, from VPC creation to connectivity testing.

🔗 Key Technologies
AWS VPC
AWS Transit Gateway
Security Groups
Network ACLs
EC2 Instances
Feel free to explore the code, documentation, and resources, and reach out if you have any questions or suggestions!
