# 🌐 Networking Protocols - Study Notes & Labs

This repository contains my personal study notes and hands-on labs based on the TryHackMe networking rooms focused on core internet protocols.

The goal is to build strong fundamentals for careers in Cybersecurity, Cloud Engineering, and Infrastructure.

---

## 📚 Topics Covered

### 🔹 Core Networking Concepts
- How the internet works
- TCP vs UDP communication
- Client-server model

### 🔹 Name Resolution
- DNS fundamentals
- Domain lookups and troubleshooting

### 🔹 Domain Intelligence
- WHOIS queries
- Domain ownership and metadata analysis

### 🔹 Web Communication
- HTTP and HTTPS fundamentals
- Manual HTTP requests using Telnet
- Understanding headers and status codes

### 🔹 File Transfer
- FTP protocol basics
- Uploading and downloading files
- Active vs Passive mode

### 🔹 Email Protocols
- SMTP – Sending emails
- POP3 – Receiving emails
- IMAP – Synchronizing mailboxes
- Manual email interaction using Telnet

---

## 🧪 Example Labs

### HTTP via Telnet
```bash
telnet <server-ip> 80
GET / HTTP/1.0
