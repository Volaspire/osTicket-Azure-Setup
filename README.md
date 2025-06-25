# osTicket-Azure-Setup
Final project for practical exam – osTicket setup on Azure.
🎓 Final Project – osTicket Support Ticket System on Azure
📝 Project Summary
This project is a step-by-step tutorial walkthrough on how to deploy the osTicket open-source support ticket system using Microsoft Azure cloud infrastructure. It covers everything from setting up virtual machines, configuring Windows Server, installing necessary components (PHP, MySQL, IIS), and securing the deployment.

👨‍💻 Languages Used
PowerShell (for VM setup and configuration)

Basic SQL (for osTicket database setup)

🖥️ Environments Used
Microsoft Azure

Windows Server 2022

Windows 10 (for admin interface access)

🛠️ Technologies / Applications / Services Used
Azure Resource Groups

Azure Virtual Machines

Azure Network Security Groups (NSGs)

Windows Server 2022

IIS (Internet Information Services)

MySQL Database

PHP

osTicket

📸 Media
Stage	Screenshot
VM Setup in Azure	
IIS Configuration	
osTicket Installation Page	
Working Support Portal	

🧪 Demonstration
The steps below detail the full demonstration of the project from start to finish:

1. Azure VM Provisioning
Created a Windows Server 2022 VM in Azure

Configured NSG rules to allow HTTP, HTTPS, and RDP traffic

Used PowerShell to install required packages

2. Server Configuration
Installed and configured IIS, PHP, and MySQL

Verified that all dependencies for osTicket were available

3. osTicket Installation
Uploaded osTicket files to IIS web directory

Created and configured MySQL database and user

Completed installation via browser

4. System Demonstration
Logged in as Admin to osTicket dashboard

Created and responded to support tickets

Showed functionality of categories, users, and workflows
