# NAT (Network Address Translation)

## Overview
NAT (Network Address Translation) allows multiple devices on a private network to share a single public IP address. It is commonly used in routers and firewalls.

## Why NAT Is Important
- Conserves public IPv4 addresses  
- Adds a layer of security by hiding internal IPs  
- Enables private networks to access the internet  

## Types of NAT

### 1. **Static NAT**
- One private IP ↔ one public IP  
- Used for servers that need to be reachable from outside  

### 2. **Dynamic NAT**
- Private IPs are mapped to a pool of public IPs  
- Mapping changes dynamically  

### 3. **PAT (Port Address Translation)**  
Also called **NAT Overload**  
- Many private IPs share one public IP  
- Differentiated by port numbers  
- Most common type used in home routers  

## Example of PAT
Private IPs:  
- 192.168.1.10  
- 192.168.1.11  

Both appear on the internet as:  
- Public IP: 203.0.113.5  
- With different port numbers  

## NAT Table
Routers maintain a NAT table to track:  
- Private IP  
- Private port  
- Public IP  
- Public port  

## NAT Limitations
- Breaks end‑to‑end connectivity  
- Some protocols don’t work well with NAT  
- Requires NAT traversal for VoIP, gaming, etc.  

## What I Learned
- NAT hides internal IPs and conserves public addresses  
- PAT is the most widely used NAT type  
- NAT is essential for IPv4 networks
