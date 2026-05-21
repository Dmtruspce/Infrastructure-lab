# Enterprise Infrastructure Lab

## Overview

This project is a hands-on enterprise infrastructure lab designed to simulate a real-world corporate IT environment using hybrid on-premises and cloud technologies.

The purpose of this lab is to demonstrate practical skills in:

- Active Directory administration
- Windows Server management
- Azure/Entra ID integration
- Group Policy management
- Networking and DNS configuration
- Endpoint deployment and management
- Hybrid identity concepts
- Enterprise troubleshooting workflows
- Security best practices within infrastructure operations

This environment is continuously evolving to reflect real-world IT operations and infrastructure administration.

---

# Project Goals

The primary goals of this lab are to:

- Build and manage a functional enterprise domain environment
- Gain hands-on experience with infrastructure technologies
- Simulate enterprise IT support and systems administration tasks
- Practice secure configuration and identity management
- Develop troubleshooting methodologies
- Document technical processes professionally
- Showcase technical growth and operational understanding

---

# Environment Architecture

## Core Components

| Component | Purpose |
|---|---|
| Windows Server | Domain Controller |
| Active Directory Domain Services | Identity Management |
| DNS Server | Name Resolution |
| DHCP Server | IP Address Management |
| Windows 11 Client | Domain-Joined Workstation |
| Azure / Entra ID | Cloud Identity Integration |
| Microsoft Intune | Endpoint Management |
| Group Policy | Enterprise Configuration Management |
| VPN Solutions | Secure Remote Connectivity |
| Microsoft Defender | Endpoint Security |

---

# Lab Topology

## Network Information

| Configuration | Value |
|---|---|
| Domain Name | deeskie.local |
| Domain Controller | DC01 |
| Client Machine | CL01 |
| Address Space | 10.10.0.0/20 |
| Environment Type | Hybrid Infrastructure |

---

# Technologies Used

## Infrastructure

- Windows Server 2022
- Windows 11 Enterprise
- Hyper-V / Virtualization
- Active Directory
- DNS
- DHCP
- Group Policy

## Cloud Technologies

- Microsoft Azure
- Microsoft Entra ID
- Microsoft Intune
- Conditional Access
- Microsoft Defender for Endpoint

## Networking

- TCP/IP
- DNS Resolution
- VPN Connectivity
- Subnetting
- Network Security Groups (NSGs)

## Administrative Tools

- PowerShell
- RSAT
- ServiceNow
- NinjaOne
- Splashtop

---

# Project Phases

## Phase 1 — Environment Deployment

### Objectives

- Create virtual infrastructure
- Configure networking
- Deploy Windows Server
- Promote Domain Controller
- Configure DNS

### Completed Tasks

- [x] Installed Windows Server
- [x] Configured static IP addressing
- [x] Installed AD DS role
- [x] Promoted DC01 to Domain Controller
- [x] Created Active Directory domain
- [x] Configured DNS

---

## Phase 2 — Client Deployment

### Objectives

- Deploy Windows 11 client
- Join workstation to domain
- Validate authentication
- Configure administrative access

### Completed Tasks

- [x] Installed Windows 11
- [x] Joined CL01 to domain
- [x] Tested domain authentication
- [x] Configured remote access

---

## Phase 3 — Group Policy Management

### Objectives

- Create organizational units
- Deploy GPOs
- Apply enterprise security settings
- Test policy enforcement

### Planned Tasks

- [ ] Password policy configuration
- [ ] Desktop restrictions
- [ ] Windows Update policies
- [ ] Drive mapping
- [ ] Security hardening policies

---

## Phase 4 — Hybrid Cloud Integration

### Objectives

- Integrate on-prem AD with Entra ID
- Configure hybrid identity
- Enroll devices into Intune
- Test compliance policies

### Planned Tasks

- [ ] Azure AD Connect
- [ ] Device registration
- [ ] Intune enrollment
- [ ] Conditional Access testing
- [ ] MFA implementation

---

# Security Practices

This project incorporates infrastructure security best practices, including:

- Least privilege administration
- MFA implementation
- Endpoint security monitoring
- Conditional Access policies
- Controlled remote administration
- Secure identity management
- Network segmentation concepts
- Policy-based management

---

# Troubleshooting & Lessons Learned

## Common Issues Encountered

| Issue | Resolution |
|---|---|
| Domain join failures | Corrected DNS configuration |
| Authentication issues | Fixed time synchronization |
| Hybrid join problems | Reconfigured enrollment policies |
| RDP access denied | Updated local security permissions |

---

# Screenshots

## Active Directory Users and Computers

_Add screenshot here_

## DNS Configuration

_Add screenshot here_

## Group Policy Configuration

_Add screenshot here_

## Azure / Intune Integration

_Add screenshot here_

---

# Future Improvements

Planned enhancements for this environment include:

- SIEM integration
- VLAN segmentation
- Certificate Services
- File server deployment
- Print server management
- WSUS deployment
- Linux server integration
- Monitoring and alerting
- Backup and disaster recovery
- Infrastructure automation with PowerShell

---

# Skills Demonstrated

- Systems Administration
- Infrastructure Support
- Enterprise Troubleshooting
- Identity & Access Management
- Endpoint Administration
- Hybrid Cloud Integration
- Documentation
- Network Administration
- Technical Problem Solving

---

# About This Project

This lab was created as a personal infrastructure engineering and enterprise administration project focused on building real-world operational experience.

The environment is designed to simulate technologies and workflows commonly found in enterprise IT environments.

---

# Author

Demetrious Price

## Connect With Me

- LinkedIn: _www.linkedin.com/in/demetrious-price-it-professional_
- GitHub: _https://github.com/Dmtruspce_
- Certifications:
  - CompTIA A+
  - Microsoft AZ-900
  - Microsoft SC-900

---

# Disclaimer

This environment is intended for educational and professional development purposes only.
