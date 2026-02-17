# Enterprise-Endpoint-Configuration-as-Code

## Overview

This repository demonstrates how endpoint security configurations can be managed using automation principles similar to Infrastructure as Code (IaC).

Rather than relying solely on manual Group Policy changes, this project applies security controls through version-controlled, auditable PowerShell automation.

## Philosophy

- Configuration should be repeatable
- Security controls should be versioned
- Changes should be auditable
- Rollback should be possible
- Endpoint management should align with cloud automation principles

## Implemented Controls

### Disable Mobile Hotspot / Internet Connection Sharing
Prevents users from bypassing enterprise network controls by disabling:
- SharedAccess service
- Internet Connection Sharing UI
- Mobile Hotspot functionality

## Future Roadmap

- BitLocker compliance reporting
- Firewall configuration enforcement
- SMB hardening
- RDP access restriction
- Centralized logging integration
- Azure automation alignment

## Author
Bobby Kirkland  
AWS Certified Solutions Architect – Associate
