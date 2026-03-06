# 🖥️ Windows Server Infrastructure Lab

## 📌 Overview

This project is a hands-on laboratory designed to simulate a **real corporate IT infrastructure** using Windows Server technologies.

The lab focuses on practicing enterprise administration tasks such as:

- Active Directory management
- Security policy implementation
- Network services configuration
- Infrastructure administration

The goal is to build practical experience with technologies commonly used in enterprise environments.

---

# 🏗️ Lab Architecture

The environment simulates a small enterprise network with the following components:

- Domain Controller
- Active Directory Domain Services
- Group Policy Management
- Network services and authentication
- Infrastructure security policies
```bash
Client PC
     │
     │
     ▼
Domain Controller
     │
     ├── Active Directory
     ├── Group Policy
     ├── Print Server
     └── Network Policy Server
```

---

# ⚙️ Technologies Used

- Windows Server
- Active Directory Domain Services (AD DS)
- Group Policy (GPO)
- Print Server
- Network Policy Server (NPS / RADIUS)
### requisitos do laboratório
```bash
## Requirements
- VirtualBox / VMware
- Windows Server ISO
- Minimum 8GB RAM
- 2 Virtual Machines
```
---

# 📂 Project Structure
```bash
windows-server-infrastructure-lab
│
├── Part-1-ActiveDirectory
├── Part-2-PrintServer
├── Part-3-NPS-RADIUS
└── Documentation
```
### documentação por etapas
```bash
docs/
│
├── 01-active-directory.md
├── 02-print-server.md
└── 03-nps-radius.md
```
---

# 🔧 Implementation Phases

## Part 1 — Active Directory Deployment

Implemented features:

- Windows Server installation
- Domain Controller promotion
- Active Directory configuration
- Administrative user creation
- Domain authentication testing
- Group Policy configuration
- USB device blocking policy

---

## Part 2 — Print Server (Planned)

Implementation goals:

- Deploy Print Server role
- Configure network printers
- Manage printer access permissions

---

## Part 3 — Network Policy Server (Planned)

Implementation goals:

- Configure NPS
- Implement RADIUS authentication
- Control network access policies

---

# 🎯 Project Objectives

This lab was created to strengthen skills in:

- Infrastructure administration
- Enterprise system management
- Security policy implementation
- Active Directory environments
- Corporate network simulation

---

# 🧪 Lab Environment

Example setup:

| Component | Technology |
|--------|--------|
| Domain Controller | Windows Server |
| Identity Management | Active Directory |
| Security Policies | Group Policy |
| Authentication | NPS / RADIUS |

---

# ⚠️ Disclaimer

This project was developed **for educational and laboratory purposes only**.

All configurations are performed in isolated virtual environments.
