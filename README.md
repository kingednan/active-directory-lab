# Active Directory Home Lab – Azure ☁️🖥️

## Overview
This lab simulates an enterprise Active Directory environment hosted entirely on Microsoft Azure. A Windows Server VM was configured as the domain controller and a second VM was joined to the domain as a client machine.

## What Was Built

### Domain Controller (Azure VM) 🏢
- Deployed Windows Server on an Azure Virtual Machine
- Assigned a static IP address to ensure consistent domain communication
- Installed and configured Active Directory Domain Services (AD DS)
- Promoted the server to Domain Controller

### Organizational Unit Structure 📁

```
USA
├── IT
├── HR
└── Accounting
```

### User Accounts 👥
- Created a domain user in the IT OU
- Created a domain user in the HR OU

### Client Machine (Azure VM) 💻
- Deployed a second Azure VM as a Windows client
- Joined the client to the domain
- Logged in successfully as the HR domain user

## Skills Demonstrated ✅
- Microsoft Azure VM deployment and configuration
- Static IP assignment and network configuration
- Active Directory installation and domain controller setup
- Organizational Unit (OU) design and hierarchy
- Domain user creation and management
- Client-to-domain joining and authentication
