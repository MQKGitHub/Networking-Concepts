### 🛡️ Networking Concepts

**Room:** [Networking Concepts — TryHackMe](https://tryhackme.com/room/networkingconcepts)  
**Status:** ✅ Completed  
**Date:** *16 May 2025*  

### 🎯 Objective
This room introduced fundamental networking concepts including the OSI and TCP/IP models, IP addressing, routing, and transport protocols (TCP/UDP). The goal was to understand how data travels across networks and how different protocols operate at each layer.

---

### 🗝️ Key Concepts  
- **OSI Model** — 7-layer conceptual framework for network communications  
- **TCP/IP Model** — 4/5-layer practical implementation used in modern networks  
- **IP Addressing** — IPv4 structure, private vs public addresses, and subnetting  
- **Transport Protocols** — Comparison of connection-oriented TCP vs connectionless UDP  
- **Encapsulation** — How data is wrapped with headers at each network layer  
- **Practical Tools** — Using `telnet` to interact with various network services  

---

### 🛠️ Tools Used
- **Network Utilities** — `ifconfig`/`ip a s` for interface configuration  
- **Telnet** — Testing connectivity to echo (port 7), daytime (port 13), and HTTP (port 80) services  
- **Wireshark** — Analysing MAC addresses in network frames (reference from room)  

---

### ⚠️ Challenges Faced
- Initially confusing OSI layer numbering (physical=1, application=7)  
- Differentiating between similar transport protocols (TCP vs UDP)  
- Understanding subnet mask notation (e.g., /24 vs 255.255.255.0)  
- Overcame by:  
  - Practising subnet calculations  
  - Hands-on telnet exercises to see protocols in action  

---

### 🧠 What I Learned
- How network communication is structured across OSI/TCP-IP layers  
- The significance of MAC addresses at Layer 2 vs IP addresses at Layer 3  
- Three-way handshake process for TCP connection establishment  
- Private IP ranges (10.0.0.0/8, 172.16.0.0/12, 192.168.0.0/16)  
- How encapsulation adds headers at each network layer  
- Practical use of telnet for protocol testing  

---

### 🌐 Real-World Application:
> Understanding these networking fundamentals is crucial for:
> - **Troubleshooting**: Identifying whether issues occur at physical, network, or application layers  
> - **Security Analysis**: Recognising attack vectors targeting specific protocol layers  
> - **Network Design**: Properly segmenting networks using subnetting  
> - **Incident Response**: Analysing packet captures by understanding encapsulation  
> The telnet exercises demonstrated how security professionals test service connectivity during vulnerability assessments.

---

### 💭 Reflections:
- Most valuable: Understanding encapsulation and protocol headers  
- Practical benefit: Ability to manually test services using telnet  
- Key takeaway: "Networking is like postal systems - MACs are local addresses, IPs are global, and ports are apartment numbers"  
