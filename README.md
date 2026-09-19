# Windows Enterprise Homelab

> 🚧 **Work in Progress**

A hands-on Windows Server enterprise homelab built to develop practical
experience in Windows infrastructure administration, automation, security,
monitoring and troubleshooting.

The environment is hosted on Proxmox and uses dedicated network segmentation
to separate Windows lab systems from the existing home network.

## Project Goals

The lab will progressively cover:

- Windows Server 2025
- Active Directory Domain Services
- Group Policy
- DNS and DHCP
- Windows file services
- PowerShell administration and automation
- Windows security and hardening
- Monitoring and troubleshooting
- Hybrid Azure administration

The environment will also provide the foundation for a future isolated
Active Directory security testing lab.

## Current Progress

### Session 00 — Lab Architecture & Foundations

🟡 In Progress

- [x] Create dedicated WINLAB VLAN
- [x] Configure network segmentation policy
- [ ] Configure Proxmox network
- [ ] Deploy initial Windows Server VM
- [ ] Validate network isolation
- [ ] Complete architecture documentation

## Documentation

- [Lab Architecture & Network Segmentation](docs/00-architecture.md)