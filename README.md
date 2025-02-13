# Active Directory Security Lab

A comprehensive security lab environment featuring Active Directory, Splunk monitoring, and security testing capabilities.

## Network Diagram

![Network Infrastructure](./assets/network-diagram.png)


## Environment Overview

- **Domain**: Webcorp
- **Internal Network**: 192.168.1.0/24 
- **Components**:
  1. **Active Directory Domain Controller**  
     - **IP Address:** 192.168.1.10  
     - **Operating System:** Windows Server 2022  

  2. **Splunk Server**  
     - **IP Address:** 192.168.1.20  
     - **Operating System:** Ubuntu Server  

  3. **Windows 10 Workstation**  
     - **IP Address:** DHCP Assigned  

  4. **Kali Linux Attacker Machine**  
     - **IP Address:** 192.168.1.100  


## Features

- Fully configured Active Directory environment
- Splunk monitoring with Universal Forwarder
- Network segmentation with firewall
- Security testing environment

## Prerequisites

- VMware/VirtualBox
- Minimum 16GB RAM recommended
- 250GB available storage
- Windows Server 2022 ISO [>url](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022)
- Ubuntu Server ISO [>url](https://ubuntu.com/download/server)
- Windows 10 Pro ISO [>url](https://www.microsoft.com/en-ca/software-download/windows10)
- Kali Linux ISO [>url](https://www.kali.org/get-kali/#kali-installer-images)
