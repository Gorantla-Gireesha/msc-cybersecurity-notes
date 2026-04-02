# ARP & MAC Addressing

## Overview
ARP (Address Resolution Protocol) is used to map an IP address to a MAC address. It operates at the boundary of Layer 2 and Layer 3 of the OSI model.

## What Is a MAC Address?
- A unique hardware address assigned to a network interface  
- 48-bit identifier  
- Example: `00:1A:2B:3C:4D:5E`  
- Used at the Data Link Layer  

## What Is ARP?
ARP resolves IP addresses to MAC addresses so devices can communicate on a local network.

### How ARP Works
1. Device broadcasts: “Who has IP 192.168.1.10?”  
2. The device with that IP replies with its MAC address  
3. Sender stores the mapping in its ARP cache  

## ARP Cache
- Temporary table storing IP-to-MAC mappings  
- Can be viewed using:  
  - `arp -a` (Windows)  
  - `ip neigh` (Linux)

## ARP Spoofing (Security Risk)
Attackers send fake ARP replies to:
- Redirect traffic  
- Perform MITM attacks  
- Steal data  

Tools used:
- arpspoof  
- ettercap  

## What I Learned
- ARP is essential for local network communication  
- MAC addresses identify devices at Layer 2  
- ARP spoofing is a common attack used in MITM scenarios
