# DNS, HTTP, and HTTPS

---

## DNS (Domain Name System)
DNS translates human-readable domain names into IP addresses.

### Example:
www.google.com → 142.250.183.36

yaml
Copy code

### DNS Record Types:
- A – IPv4 address
- AAAA – IPv6 address
- MX – Mail server
- CNAME – Alias

---

## HTTP (HyperText Transfer Protocol)
HTTP is a protocol used for transmitting web data.

### Characteristics:
- Stateless
- Data sent in plain text
- Vulnerable to attacks like sniffing and MITM

---

## HTTPS (HyperText Transfer Protocol Secure)
HTTPS is the secure version of HTTP.

### Features:
- Uses SSL/TLS encryption
- Protects data confidentiality and integrity
- Prevents eavesdropping and tampering

---

## HTTP vs HTTPS

| HTTP | HTTPS |
|----|----|
| No encryption | Encrypted |
| Insecure | Secure |
| Port 80 | Port 443 |

---

## Importance in Cybersecurity
- DNS attacks can redirect traffic
- HTTP traffic can be intercepted
- HTTPS protects sensitive information

---

## Conclusion
Understanding DNS, HTTP, and HTTPS is critical for both attackers and defenders in cybersecurity.