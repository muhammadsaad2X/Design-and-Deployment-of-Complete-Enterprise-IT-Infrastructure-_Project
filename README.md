# Design-and-Deployment-of-Complete-Enterprise-IT-Infrastructure-Project
## Project Type
Self-Implemented Home Lab Project

## Training Reference
Concepts and hands-on practice learned during (System Administrator Course) at MRGT Institute.
## Project Overview
This project is an **enterprise IT infrastructure setup** for Contoso Company. It involved creating multiple virtual machines using VMware Workstation Pro, installing Windows Server 2019 Servers and Windows 10 clients for users, and configuring key services such as Active Directory Domain Services, DNS, DHCP, Certificate Services, File Servers with DFS replication, Admin center and a VPN server. The setup ensures centralized management, secure communication, automated services, and high availability for daily operations.

## Servers and Services Configured

###  Window Admin Center 
- **For Remotely Managed All server**
  
### Active Directory Domain service
- **Centralized Management All Users**

### 1. Domain Controllers
- **Primary Domain Controller (DC1)** and **Replica Domain Controller (DC2)**  
- Installed and configured **Active Directory Domain Services (AD DS)**  
- Managed **Users, Groups, and Organizational Units (OUs)**  
- Ensured **domain replication** and **high availability**

### 2. DNS Server
- Configured **DNS zones** (Forward and Reverse Lookup)  
- Set up **Conditional Forwarders** for external domain resolution  
- Integrated DNS with Active Directory for **secure name resolution**

### 3. DHCP Server
- Configured **IP address pools** for dynamic allocation  
- Assigned **static IP addresses** to servers  
- Set up **DHCP reservations** and options for client PCs

### 4. Certificate Services (AD CS)
- Installed **Certificate Authority (CA)** for secure authentication  
- Issued certificates for **domain-joined machines and users**

### 5. Windows Admin Center
- Deployed **Windows Admin Center** for centralized server management  
- Monitored server health, services, and performance from a single interface

### 6. Storage + File server
- Created **Storage Pools** with **Mirror Virtual Disks** (RAID 1)  
- Configured **File Servers** for shared data  
- Implemented **DFS Namespace and Replication** for redundancy and high availability

### 7. VPN Server
- Configured **RRAS with NAT** to provide secure remote access  
- Allowed **remote clients** to connect safely to the internal network

### 8. Group Policy Objects (GPOs)
- Created **GPOs** for user restrictions and security policies  
- Enforced **password policies, desktop restrictions, and software installation rules**

### 9. Testing On User
- Verified **domain login** from Windows 10 clients  
- Tested **DNS resolution, DHCP IP assignment, VPN connectivity, and file access**  
- Ensured all services are **working properly** and highly available

## Project Highlights
- **Centralized Management:** Active Directory + Windows Admin Center  
- **Secure Communication:** Certificates + VPN + GPOs  
- **High Availability:** Replica DC, DFS Replication, Storage Mirroring  
- **Scalable Infrastructure:** Supports future expansion of Contoso Company

## Documentation
Full documentation and detailed setup steps are available in **Project_Documentation.PDF** 
