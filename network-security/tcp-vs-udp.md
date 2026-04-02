# TCP vs UDP

## Overview
TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are two core transport layer protocols. They define how data is transmitted between devices over a network.

## TCP (Transmission Control Protocol)
- Connection-oriented
- Reliable delivery (acknowledgments, retransmissions)
- Slower but accurate
- Ensures data arrives in order
- Used when accuracy matters

### Common Uses
- Web browsing (HTTP/HTTPS)
- Email (SMTP)
- File transfer (FTP)
- SSH

## UDP (User Datagram Protocol)
- Connectionless
- No guarantee of delivery
- Faster but less reliable
- No ordering or retransmission
- Used when speed matters

### Common Uses
- Video streaming
- Online gaming
- VoIP calls
- DNS queries

## Key Differences

| Feature | TCP | UDP |
|--------|-----|-----|
| Connection | Yes | No |
| Reliability | High | Low |
| Speed | Slower | Faster |
| Ordering | Guaranteed | Not guaranteed |
| Overhead | High | Low |

## What I Learned
- TCP is reliable but slower  
- UDP is fast but may drop packets  
- Choosing TCP or UDP depends on the application’s needs
