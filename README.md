# 🎓 Final Project – osTicket Support Ticket System on Azure

## 📝 Project Summary

This project is a step-by-step walkthrough for deploying the open-source **osTicket support ticket system** on **Microsoft Azure**. The goal is to demonstrate how to use cloud services and server configuration to host a real-world IT solution.

This project is part of a practical final exam for an IT course and is designed to showcase infrastructure deployment and system configuration skills to potential employers.

### 👨‍💻 Languages Used
- PowerShell (for VM setup and basic scripting)
- SQL (for database creation and user configuration)

### 🖥️ Environments Used
- Microsoft Azure
- Windows Server 2022 (hosted on Azure VM)
- Windows 10 (local client used for remote desktop and admin access)

### 🛠️ Technologies / Applications / Services Used
- Azure Resource Groups
- Azure Virtual Machines
- Azure Network Security Groups (NSG)
- IIS (Internet Information Services)
- MySQL Database
- PHP
- osTicket

---

## 📸 Media

Below are images from various stages of the project:

| Stage | Screenshot |
|-------|------------|
| ✅ VM Provisioned on Azure | ![VM Setup](images/vm-setup.png) |
| 🔧 IIS and PHP Installed | ![IIS Config](images/iis-config.png) |
| 🧰 osTicket Installation Wizard | ![osTicket Install](images/osticket-install.png) |
| 📨 Working Support Ticket Portal | ![osTicket Portal](images/osticket-portal.png) |

> _Note: All screenshots are stored in the `/images` folder in this repository._

---

## 🧪 Demonstration

### 1. Azure VM Deployment
- Created a new **Windows Server 2022** virtual machine on Microsoft Azure.
- Set up **Network Security Group (NSG)** rules to allow RDP, HTTP, and HTTPS traffic.

### 2. Server Configuration
- Installed **IIS**, **PHP**, and **MySQL** on the VM.
- Configured **MySQL** and created a database for osTicket.

### 3. Installing osTicket
- Downloaded and extracted osTicket files into IIS web root directory.
- Completed setup using the web-based installation wizard.
- Created and configured an admin user and system settings.

### 4. Testing & Verification
- Logged into the **osTicket Admin Panel**.
- Created test tickets and responded as an agent.
- Verified full ticket lifecycle from creation to resolution.

---

## 🚀 Project Outcomes

- Demonstrated cloud infrastructure setup and security configuration.
- Successfully deployed a production-ready support ticket system.
- Gained hands-on experience with PowerShell, IIS, MySQL, and PHP on Windows Server.

---

## 📁 Folder Structure

/images/
├── vm-setup.png
├── iis-config.png
├── osticket-install.png
└── osticket-portal.png
