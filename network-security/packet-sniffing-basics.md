# Packet Sniffing Basics

## Overview
Packet sniffing is the process of capturing and analyzing network traffic. It helps understand how data flows across a network and is used for troubleshooting, monitoring, and security analysis.

## Why Packet Sniffing Is Important
- Detect suspicious activity  
- Analyze network performance  
- Troubleshoot connectivity issues  
- Understand protocols and traffic patterns  

## Common Tools
- **Wireshark** – GUI-based packet analyzer  
- **tcpdump** – Command-line packet capture tool  
- **tshark** – Terminal version of Wireshark  

## What Packet Sniffers Capture
- Source and destination IPs  
- Ports  
- Protocols (TCP, UDP, ICMP)  
- Payload data (if not encrypted)  
- Flags, sequence numbers, timestamps  

## Promiscuous Mode
- Allows a network interface to capture all packets  
- Not just those addressed to the device  

## Legal & Ethical Considerations
- Only sniff traffic you are authorized to analyze  
- Unauthorized sniffing is illegal and unethical  

## What I Learned
- Packet sniffing is essential for network forensics  
- Tools like Wireshark reveal deep protocol details  
- Encryption prevents sniffers from reading sensitive data
