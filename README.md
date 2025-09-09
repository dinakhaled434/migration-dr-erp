# Migration & DR Setup for a Manufacturing Company

## Project Overview
This project involves migrating an on-premises ERP system of a manufacturing company to Microsoft Azure with a secure, scalable, and highly available infrastructure. It also implements an Active/Passive Disaster Recovery (DR) strategy.

## Key Azure Services Used
- Azure Landing Zone (Firewall, Bastion, VPN Gateway)
- Azure Front Door (Global routing & failover)
- SQL Server (Azure-hosted + Azure Arc)
- IIS-based Application Servers
- File Servers (Azure File Share + Blob Storage)
- VPN Point-to-Site (P2S)
- Azure Site Recovery (ASR)
- Azure Monitor + Log Analytics
- Forced Tunneling + VNet Peering

## Project Structure

migration-dr-erp/
├─ docs/ # Project documentation (PDFs, Excel)
├─ scripts/ # Scripts for automation
├─ diagrams/ # Architecture diagrams
├─ config/ # Configuration files
├─ tests/ # Test scripts
└─ .gitignore
