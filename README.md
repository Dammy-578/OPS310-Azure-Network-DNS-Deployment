# OPS310-Azure-Network-DNS-Deployment
Azure-based network simulation using domain controller, web server, client VM, and private DNS. Virtual network peering and DNS resolution across VMs. Completed for OPS310 at Seneca Polytechnic.
# Azure Network & DNS Access Simulation – OPS310 Project 1

**Course:** OPS310 – Cloud Platform Management  
**Date:** November 2024  
**Institution:** Seneca Polytechnic

---

## 🧠 Overview
This project simulates the deployment of a traditional enterprise application architecture in Microsoft Azure. The environment includes a domain controller, web server, and client VM — all hosted on separate virtual networks and connected via peering. A private DNS zone is used to allow name resolution across networks.

---

## ☁️ Azure Components Used
- Azure Virtual Machines (Windows Server 2019 & Windows 10)
- Virtual Networks and Subnets (3 separate VNETs)
- Private DNS Zone (`ops310.com`)
- Virtual Network Peering (regional and global)

---

## 🛠️ Key Tasks
- Deployed 3 VMs: domain controller, web server (IIS), and Windows client
- Set up Active Directory Domain Services (ADDS) on `dc-vm`
- Joined the web server to the domain and enabled IIS
- Configured a private DNS zone with a record pointing to the web server
- Linked the DNS zone to VNet2 and VNet3
- Verified domain-based web access from the client VM to `project1.ops310.com`

---

## 🧠 Skills Demonstrated
- Microsoft Azure  
- Virtual Networking  
- DNS Configuration & Resolution  

---

## 📂 Notes
The project was submitted in video format as a live walkthrough. Screenshots were not retained, but all steps were completed, recorded, and validated.

---

## ✅ Project Status
- ✔️ Fully deployed and tested in Azure  
- ✔️ DNS resolution successful across peered networks  
- ✔️ Project submitted and verified
