# Building a Multi-VM Cybersecurity Lab
---   
## 📌 Project Overview

This project documents the step-by-step process of building a multi-machine cybersecurity lab environment using virtualization.

The goal of this lab was to:

- Simulate a small enterprise network
- Configure internal networking between machines
- Install both attacker and target systems
- Prepare an environment for penetration testing and security monitoring practice

This lab serves as a foundation for:

- Active Directory testing
- Network analysis
- Blue team and red team simulations
- Incident response practice

---

## 🛠️ Technologies & Tools Used

- Oracle VM VirtualBox
- Windows 8
- Windows Server
- Kali Linux

## 🖥️ Virtualization Setup
### 1. VirtualBox Installation

- Installed VirtualBox Manager
- Configured base settings
- Allocated RAM, CPU, and storage for each VM
- Created virtual hard disks for operating systems

This provided the virtualization layer required to run multiple systems simultaneously on one Host machine.

## 🖥️ Virtual Machines Deployed
### 🔹 Windows 8 Client Machine

Purpose:

- Acts as an end-user workstation
- Used for domain join testing
- Used for privilege escalation testing
- Used to simulate compromised endpoints

Configuration:

- Installed Windows 8 OS
- Allocated appropriate RAM and disk space
- Connected to internal NAT network

### 🔹🔹 Windows Server Machine

Purpose:

- Acts as a domain controller (future AD lab use)
- Central authentication server
- Network management and policy control

Configuration:

- Installed Windows Server
- Assigned to same NAT network
- Prepared for Active Directory configuration

### 🔹🔹🔹 Kali Linux Machine

Purpose:

- Offensive security testing
- Network scanning
- Enumeration and exploitation testing

Installed:

- Kali Linux ISO
- Configured network settings
- Verified connectivity with other VMs

This machine will be used for:

- Nmap scanning
- Password attacks
- Exploitation practice
- Network monitoring exercises

---   

## 🌐 Network Configuration
### NAT Network Configuration

A NAT Network was created to allow:

- Communication between virtual machines
- Isolated lab testing
- Internet access (if required)
- Segmentation from the host machine

This setup simulates a small internal enterprise network environment.

---   

### 🔐 Security Objectives of This Lab

This lab enables hands-on practice in:

- Network reconnaissance
- Vulnerability scanning
- Active Directory attacks and defenses
- Packet analysis using Wireshark
- Log analysis
- Malware simulation testing
- Blue team monitoring scenarios

---   

## Skills Demonstrated

- Virtual machine provisioning
- Network segmentation
- Operating system installation
- Lab environment design
- Cybersecurity test environment preparation
- Infrastructure documentation

---   

## Future Enhancements

- Promote Windows Server to Domain Controller
- Install Active Directory Domain Services
- Deploy Sysmon for endpoint logging
- Forward logs to a SIEM (e.g., Splunk)
- Implement Group Policy Objects (GPO)
- Create additional attacker/target machines
- Simulate phishing or credential attacks

---   

 ## Why This Lab Matters

- Building a personal cybersecurity lab demonstrates:
- Practical technical ability
- Understanding of enterprise network structure
- Hands-on security testing capability
- Readiness for SOC / Security Analyst roles

This lab serves as a controlled environment for continuous cybersecurity learning and experimentation.

---

### **Author**   
Olanipekun Babatunde

