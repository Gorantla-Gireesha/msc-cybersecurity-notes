# Network Protocols

## Overview
Network protocols define rules for communication between devices. They ensure data is transmitted, received, and interpreted correctly across networks.

## Common Network Protocols

### 1. **HTTP / HTTPS**
- Used for web browsing  
- HTTPS adds encryption using TLS  
- Port 80 (HTTP), Port 443 (HTTPS)

### 2. **DNS (Domain Name System)**
- Converts domain names to IP addresses  
- Example: google.com → 142.250.190.14  
- Port 53

### 3. **DHCP (Dynamic Host Configuration Protocol)**
- Automatically assigns IP addresses  
- Reduces manual configuration  
- Ports 67/68

### 4. **FTP / SFTP**
- File transfer protocols  
- FTP is insecure  
- SFTP uses SSH for encryption  
- Ports 20/21 (FTP), Port 22 (SFTP)

### 5. **SSH (Secure Shell)**
- Secure remote login  
- Encrypted communication  
- Port 22

### 6. **SMTP / POP3 / IMAP**
- Email protocols  
- SMTP → sending  
- POP3/IMAP → receiving  
- Ports: 25, 110, 143

### 7. **SNMP**
- Used for network monitoring  
- Common in routers, switches  
- Ports 161/162

## Why Protocols Matter in Cybersecurity
- Attackers often target protocol weaknesses  
- Misconfigured protocols lead to vulnerabilities  
- Understanding ports helps in firewall and IDS rules

## What I Learned
- Protocols define how devices communicate  
- Each protocol has a specific purpose and port  
- Secure versions (HTTPS, SFTP) protect data in transit
