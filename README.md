# AWS VPC Peering Project (Dev ↔ Prod)

## Project Overview
This project demonstrates secure private communication between two AWS Virtual Private Clouds (VPCs) — Development (Dev) and Production (Prod) — using VPC Peering.  
The setup enables resources in one VPC to communicate with another VPC using private IP addresses without traversing the public internet.

---

## Architecture
- Dev VPC (Application VPC)
- Prod VPC (Service VPC)
- VPC Peering Connection
- EC2 Instances for testing

---

## Network Design

| VPC Name | CIDR Block |
|---------|------------|
| Dev VPC | 10.1.0.0/24 |
| Prod VPC | 10.0.0.0/16 |

- Non-overlapping CIDR blocks
- Private IP communication

---

## AWS Services Used
- Amazon VPC
- VPC Peering
- Amazon EC2
- Route Tables
- Subnetting
- Internet Gateway
- Security Groups

---
<img width="1443" height="763" alt="image" src="https://github.com/user-attachments/assets/b4c4fb8f-0728-48a8-9262-c6e0e832830b" />

<img width="1919" height="987" alt="Screenshot 2025-12-31 125224" src="https://github.com/user-attachments/assets/7f678a91-c7dc-4f01-a6bc-0734f98fe13e" />

<img width="1920" height="985" alt="Screenshot 2025-12-31 125300" src="https://github.com/user-attachments/assets/a53a68ea-8bb4-46ce-8503-be1633b7f459" />

<img width="1919" height="981" alt="Screenshot 2025-12-31 125323" src="https://github.com/user-attachments/assets/d62ad669-8227-4411-8835-9a70ca2ab608" />

<img width="1919" height="973" alt="Screenshot 2025-12-31 125346" src="https://github.com/user-attachments/assets/5bca1389-1b74-4b79-9005-3c8ae0c04a57" />

<img width="1900" height="993" alt="Screenshot 2025-12-31 125540" src="https://github.com/user-attachments/assets/fd48e1e8-b7e0-421a-a2e8-565bee4fe217" />

<img width="1900" height="1026" alt="Screenshot 2025-12-31 130430" src="https://github.com/user-attachments/assets/66406bdc-bc09-458a-9672-a4bf4c0b603f" />

