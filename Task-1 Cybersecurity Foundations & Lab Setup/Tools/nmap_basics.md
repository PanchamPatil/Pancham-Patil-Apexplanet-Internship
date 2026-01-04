# Nmap Basics

Nmap (Network Mapper) is an open-source tool used for network discovery and security auditing.

---

## Why Use Nmap?
- Discover live hosts
- Identify open ports
- Detect running services
- Perform basic vulnerability scanning

---

## Common Nmap Commands

### Basic Scan
```bash
nmap 192.168.1.1

Scan Multiple Hosts
nmap 192.168.1.0/24

TCP SYN Scan
nmap -sS 192.168.1.1

Service Version Detection
nmap -sV 192.168.1.1

OS Detection
nmap -O 192.168.1.1

Nmap in Cybersecurity

Nmap is widely used by security professionals to identify exposed services and potential attack surfaces.