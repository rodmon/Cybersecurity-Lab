# Laboratory Architecture

## Purpose

This document describes the Week 1 cybersecurity laboratory architecture.

## High-Level Design

```text
                         INTERNET
                            |
                            |
                    WINDOWS 11 HOST
                            |
                     ORACLE VIRTUALBOX
                            |
                    NAT NETWORK
                    10.0.0.0/24
                            |
                            |
                     KALI LINUX VM
                      10.0.0.2/24
                            |
                   CYBERSECURITY LAB
```

## Components

| Component | Role |
|---|---|
| Windows 11 | Physical host |
| VirtualBox | Hypervisor |
| NAT Network | Virtual network |
| Kali Linux | Security testing machine |
| `/downloads` | Shared host/VM directory |

## Addressing

- Network: `10.0.0.0/24`
- Kali Linux: `10.0.0.2/24`

## Design Principles

The Week 1 design emphasizes:

- Controlled testing boundaries
- Network isolation from production environments
- Reproducibility
- Expandability
- Evidence-based validation
- Authorized cybersecurity testing

## Future Expansion

The architecture can be extended with additional authorized laboratory systems, such as:

- Windows client
- Windows Server
- Linux server
- Vulnerable web application
- Database server
- Security monitoring/SIEM platform
- Network traffic analysis platform

Any future expansion should remain within the authorized laboratory environment.
