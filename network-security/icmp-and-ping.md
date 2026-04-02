# ICMP & Ping

## Overview
ICMP (Internet Control Message Protocol) is used for sending error messages and operational information across a network. It is essential for troubleshooting and diagnostics.

## What Is ICMP?
- Works at the Network Layer (Layer 3)
- Used for reporting errors, unreachable hosts, and network issues
- Not used for sending actual data

## Common ICMP Messages
- **Echo Request** – sent by ping
- **Echo Reply** – response to ping
- **Destination Unreachable**
- **Time Exceeded**
- **Redirect Message**

## What Is Ping?
Ping is a tool that uses ICMP to test connectivity between two devices.

### What Ping Shows
- Whether the host is reachable
- Round-trip time (latency)
- Packet loss
- TTL (Time To Live)

### Example Command

ping google.com


## Security Considerations
- ICMP can be used for reconnaissance
- Attackers may use ping sweeps to find live hosts
- Some firewalls block ICMP to prevent scanning

## What I Learned
- ICMP helps diagnose network issues
- Ping uses ICMP Echo Request/Reply
- ICMP can be abused for scanning and attacks

