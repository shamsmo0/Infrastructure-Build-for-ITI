# MCSA Final Project – Windows Server Infrastructure

This repository contains the full implementation of the MCSA Final Project Scenario for ITI, delivering a complete multi-site Windows Server infrastructure including AD DS, DNS, DHCP, GPO, RODC, IIS Web Server, and WSUS. The project simulates a real enterprise environment across Smart Village HQ and three branches (Alexandria, Ismailia, Arish).

## Project Scope

Full Active Directory Domain Services deployment
DNS & DHCP configuration for all sites
Group Policy for security, restrictions, software deployment & USB blocking
RODC deployment in Arish
IIS Web Server hosting web1/web2
WSUS Server for centralized updates
Multi-site environment: ITI.local, Alex.ITI.local, Ism.ITI.local

## Key Implementations

OU structure for departments: HR, Finance, IT Support
User creation, groups, and delegated permissions
Login restrictions by device and time
Roaming profiles
Flash drive blocking for Finance
Wallpaper enforcement
Software deployment (WinRAR) via GPO
DNS secondary zone for web2.com
RDP delegation for non-admin accounts
Local user on PC6 managing the web server via RDP + FTP access

## Topology Components

DC1 – PDC + DNS
DC2 – Additional DC
DC3 – RODC (Arish)
DC4 / DC5 – Child DCs (Alex & Ismailia)
DC6 – WSUS
IIS Web Server hosting: www.web1.com, www.web2.com

## Deliverables Included

Network diagram
Complete documentation
GPO & DNS configurations
Web & FTP server setup
WSUS configuration steps
🎯 Goal

To design, deploy, and document a realistic, secure, and fully functional Windows Server enterprise infrastructure suitable for MCSA training and demonstration.
