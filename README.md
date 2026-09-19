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
- [x] Configure Proxmox network
- [x] Deploy initial Windows Server VM (DC01; AD DS promotion pending)
- [x] Verify blocked test traffic to PLAN, DMZ, Default and LAN
- [x] Verify gateway, external DNS, outbound TCP 443 and inbound RDP access
- [x] Verify a new connection from DC01 to the administration workstation is blocked
- [ ] Verify clean-install snapshot and restore
- [ ] Complete VM templates and VLAN break/fix exercise
- [ ] Complete architecture documentation

## Documentation

- [Lab Architecture & Network Segmentation](docs/00-architecture.md)