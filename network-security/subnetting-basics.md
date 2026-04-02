# Subnetting Basics

## Overview
Subnetting is the process of dividing a large network into smaller, more manageable subnetworks. It improves security, reduces congestion, and organizes network structure.

## Why Subnetting Is Important
- Efficient IP address usage  
- Better network performance  
- Improved security segmentation  
- Easier troubleshooting  

## Key Terms
### **IP Address**
A unique identifier for a device on a network.  
Example: 192.168.1.10

### **Subnet Mask**
Defines which part of the IP is network vs host.  
Example: 255.255.255.0

### **CIDR Notation**
Short form of subnet mask.  
Example: /24 = 255.255.255.0

## Common CIDR Blocks
| CIDR | Hosts Available | Subnet Mask |
|------|-----------------|-------------|
| /24  | 254 hosts       | 255.255.255.0 |
| /25  | 126 hosts       | 255.255.255.128 |
| /26  | 62 hosts        | 255.255.255.192 |
| /30  | 2 hosts         | 255.255.255.252 |

## How to Calculate Subnets
1. Determine required hosts  
2. Choose appropriate CIDR  
3. Calculate network, broadcast, and host range  

### Example
Network: 192.168.1.0/24  
Subnet into /26 blocks:

- Subnet 1: 192.168.1.0 – 63  
- Subnet 2: 192.168.1.64 – 127  
- Subnet 3: 192.168.1.128 – 191  
- Subnet 4: 192.168.1.192 – 255  

## What I Learned
- Subnetting organizes networks into smaller segments  
- CIDR notation simplifies subnet masks  
- Subnetting improves performance and security
