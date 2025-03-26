# Homelab
Hacking in a virtual enviroment

# 🏴‍☠️ My First Homelab: Kali Linux & Mr. Robot in VirtualBox  

## 🚀 Overview  
This project is my first **cybersecurity homelab** setup. I created a virtualized environment using **VirtualBox** to practice **ethical hacking** and **penetration testing** techniques.  

### 🖥️ Machines in the Lab  
- **Attacker Machine**: Kali Linux  
- **Target Machine**: Mr. Robot CTF VM  
- **Networking**: Isolated **internal network** (no internet access)  
- **IP Assignment**: DHCP within the internal network  

## ⚙️ Setup Details  
### 🔹 Virtualization  
- **Platform**: VirtualBox  
- **Operating Systems**: Kali Linux & Mr. Robot CTF VM  
- **ISO/OVA Sources**:  
  - Kali Linux: [Official Kali Website](https://www.kali.org/)  
  - Mr. Robot VM: [VulnHub](https://www.vulnhub.com/)  

### 🔹 Network Configuration  
- **Network Type**: **Internal Network** (isolated from main network)  
- **IP Addresses**: Assigned dynamically via **DHCP**  

📷 **Screenshot**: *VirtualBox Network Settings*  
![VirtualBox Network Settings](screenshots/virtualbox-network.png)  

## 🎯 Goals  
- 🔍 **Scan & Enumerate** the Mr. Robot VM using **Nmap**  
- 🛠️ **Identify vulnerabilities** and exploit them  
- 🚀 **Practice privilege escalation & web exploitation**  
- 📝 **Document findings and learnings**  

📷 **Screenshot**: *Kali Linux Nmap Scan*  
![Nmap Scan](screenshots/nmap-scan.png)  

## 🛠️ Next Steps  
1. Perform an **Nmap scan** to discover open ports  
2. Use **Dirb** or **Gobuster** for directory enumeration  
3. Analyze web vulnerabilities & attempt exploits  
4. Document results and share insights  

---

💡 **Excited to dive deeper into ethical hacking!** 🔥 Let’s break, learn, and secure! 🏴‍☠️  
