# WEEK 1 INTERNSHIP PROJECT REPORT

## Design and Setup of a Cybersecurity Testing Laboratory Environment

| **Item** | **Details** |
|---|---|
| **Internship Programme** | Cybersecurity Internship |
| **Organization** | Networkwalks |
| **Reporting Period** | Week 1 |
| **Project** | Cybersecurity Testing Laboratory Environment |
| **Host Operating System** | Windows 11 |
| **Virtualization Platform** | Oracle VirtualBox |
| **Security Testing OS** | Kali Linux |
| **Laboratory Network** | `10.0.0.0/24` |
| **Kali Linux IP Address** | `10.0.0.2/24` |
| **Repository** | `rodmon/Cybersecurity-Lab` |

---

## 1. Internship Context

This project forms part of my **Cybersecurity Internship at Networkwalks**.

The internship provides practical exposure to areas including:

- Network security
- Vulnerability assessment
- Penetration testing
- Security operations
- Incident response
- Digital forensics
- Risk assessment
- Cybersecurity governance and best practices

The primary objective of Week 1 was to establish a **controlled, isolated and reusable cybersecurity laboratory environment** that can support subsequent practical cybersecurity exercises.

---

## 2. Introduction

During the first week of the internship, I designed and configured a controlled cybersecurity testing laboratory using a **Windows 11 host computer**, **Oracle VirtualBox**, and **Kali Linux**.

Kali Linux was deployed as the primary cybersecurity testing machine. The virtual environment was configured using a **VirtualBox NAT Network** with the `10.0.0.0/24` IPv4 subnet.

The laboratory provides a controlled environment in which cybersecurity concepts, network security techniques, reconnaissance, vulnerability assessment, penetration testing, security monitoring and other authorized security activities can be practiced without unnecessarily interacting with production infrastructure.

The environment was also designed with future expansion in mind, allowing additional virtual machines to be introduced as required.

---

## 3. Week 1 Objectives

The objectives of Week 1 were to:

1. Establish a functional cybersecurity testing laboratory.
2. Prepare the Windows 11 host environment.
3. Install and configure Oracle VirtualBox.
4. Deploy Kali Linux as the primary cybersecurity testing machine.
5. Configure a dedicated laboratory network.
6. Establish the `10.0.0.0/24` laboratory subnet.
7. Configure Kali Linux with the address `10.0.0.2/24`.
8. Provide Internet connectivity for legitimate updates and security research.
9. Configure controlled clipboard integration.
10. Enable controlled file drag-and-drop functionality.
11. Configure the `/downloads` shared folder.
12. Validate basic connectivity and laboratory functionality.
13. Establish a reusable environment for subsequent cybersecurity exercises.
14. Document the configuration and supporting evidence in GitHub.

---

## 4. Technologies and Tools Used

| **Technology / Tool** | **Purpose** |
|---|---|
| **Windows 11** | Host operating system |
| **Oracle VirtualBox** | Virtualization platform |
| **Kali Linux** | Cybersecurity testing operating system |
| **VirtualBox NAT Network** | Laboratory network connectivity |
| **IPv4** | Network addressing |
| **`10.0.0.0/24`** | Laboratory network subnet |
| **Shared Folder** | Controlled file exchange |
| **Clipboard Integration** | Controlled host-to-VM text exchange |
| **Drag-and-Drop** | Controlled file transfer |
| **Git** | Version control |
| **GitHub** | Documentation and evidence repository |

---

## 5. Laboratory Architecture

The laboratory was designed around a Windows 11 host running Oracle VirtualBox.

The primary virtual machine is Kali Linux, which is connected to a dedicated VirtualBox NAT Network.

### 5.1 Network Parameters

| **Parameter** | **Configuration** |
|---|---|
| Network Type | VirtualBox NAT Network |
| Network Address | `10.0.0.0/24` |
| Subnet Mask | `255.255.255.0` |
| Kali Linux IP | `10.0.0.2/24` |
| Addressing | IPv4 |
| Internet Access | Enabled |
| Purpose | Authorized cybersecurity laboratory activities |

### 5.2 Logical Topology

```text
                         INTERNET
                             |
                             |
                     +---------------+
                     |   Windows 11  |
                     |     HOST      |
                     +---------------+
                             |
                             |
                     +---------------+
                     |    Oracle     |
                     |   VirtualBox  |
                     +---------------+
                             |
                             |
              +-----------------------------+
              | VirtualBox NAT Network      |
              | Network: 10.0.0.0/24        |
              +-----------------------------+
                             |
                             |
                     +---------------+
                     |  Kali Linux   |
                     |  10.0.0.2/24  |
                     |               |
                     | Security      |
                     | Testing VM    |
                     +---------------+
```

The architecture provides a controlled environment for practical cybersecurity exercises while allowing legitimate Internet connectivity.

---

## 6. Virtual Machine Configuration

Kali Linux was deployed as the primary cybersecurity testing virtual machine.

The following configuration was established:

- Kali Linux operating system deployed in Oracle VirtualBox.
- VirtualBox NAT Network configured.
- Laboratory subnet configured as `10.0.0.0/24`.
- Kali Linux assigned `10.0.0.2/24`.
- Internet connectivity enabled.
- Clipboard integration enabled.
- File drag-and-drop enabled.
- `/downloads` shared folder configured.
- Laboratory environment prepared for future security testing.

The resulting environment provides a repeatable platform for subsequent cybersecurity exercises.

---

## 7. Network Configuration

The laboratory network uses the following addressing scheme:

```text
Network:        10.0.0.0/24
Subnet Mask:    255.255.255.0
Kali Linux:     10.0.0.2/24
```

The `/24` subnet provides sufficient addressing capacity for future expansion of the laboratory.

Additional virtual machines can subsequently be added to represent:

- Windows servers
- Linux servers
- Client workstations
- Vulnerable systems
- Web application targets
- Monitoring systems
- Security infrastructure
- Network services

This will allow the laboratory to evolve from a single-machine environment into a more representative cybersecurity testing network.

---

## 8. Host and VM Integration

To support practical administration and controlled file exchange, several VirtualBox integration features were configured.

### 8.1 Shared Folder

A shared `/downloads` directory was established between the Windows host and Kali Linux VM.

The shared directory provides a controlled mechanism for transferring legitimate:

- Security tools
- Scripts
- Documentation
- Configuration files
- Lab resources
- Evidence files

### 8.2 Clipboard Integration

Clipboard integration was enabled to facilitate controlled transfer of text and commands between the Windows host and Kali Linux.

### 8.3 Drag-and-Drop

File drag-and-drop functionality was enabled to support controlled transfer of laboratory files between the host and virtual machine.

These features are intended strictly for authorized laboratory activities.

---

## 9. Laboratory Validation

Following configuration, the laboratory environment was reviewed to confirm that the major components were operational.

Validation covered:

- Virtual machine availability
- Kali Linux deployment
- Network configuration
- IP address assignment
- Internet connectivity
- VirtualBox NAT Network configuration
- Clipboard functionality
- Drag-and-drop functionality
- Shared folder configuration

The supporting evidence is maintained within the project repository.

### Evidence Repository

Week 1 evidence is maintained under:

```text
evidence/
└── week-01/
```

The laboratory documentation is organized into separate sections covering architecture, configuration, evidence and reporting.

---

## 10. Security Considerations

Security was considered during the design of the laboratory to ensure that practical cybersecurity exercises remain within an authorized and controlled environment.

### 10.1 Authorized Testing

All future scanning, enumeration, vulnerability assessment, exploitation and related security activities will be restricted to:

- Laboratory systems under my control; or
- Systems for which explicit authorization has been provided.

Unauthorized testing of third-party or production systems is outside the scope of this project.

### 10.2 CIA Triad

The laboratory design supports the three core principles of information security:

| **Principle** | **Laboratory Application** |
|---|---|
| **Confidentiality** | Testing is performed within a controlled laboratory environment. |
| **Integrity** | Configuration and documentation are maintained through version control. |
| **Availability** | The virtual environment provides a reusable platform for continued practical exercises. |

### 10.3 Isolation and Risk Reduction

Using a virtualized laboratory reduces the likelihood of unintentionally affecting production systems during cybersecurity experimentation.

The environment also provides a controlled platform for learning security techniques before applying relevant concepts to appropriately authorized environments.

---

## 11. Work Completed During Week 1

The following activities were completed:

- [x] Defined cybersecurity laboratory requirements.
- [x] Prepared Windows 11 host environment.
- [x] Installed and configured Oracle VirtualBox.
- [x] Deployed Kali Linux.
- [x] Configured VirtualBox NAT Network.
- [x] Established `10.0.0.0/24` laboratory subnet.
- [x] Configured Kali Linux with `10.0.0.2/24`.
- [x] Established Internet connectivity.
- [x] Enabled clipboard integration.
- [x] Enabled file drag-and-drop.
- [x] Configured `/downloads` shared folder.
- [x] Validated the laboratory environment.
- [x] Established the foundation for subsequent cybersecurity exercises.
- [x] Documented the work in GitHub.

---

## 12. Skills Demonstrated

Week 1 provided practical exposure to the following technical skills.

### Infrastructure and Virtualization

- Virtual machine deployment
- Oracle VirtualBox administration
- Virtual network configuration
- Host/VM integration

### Networking

- IPv4 addressing
- CIDR notation
- Subnet configuration
- NAT networking
- Basic network connectivity validation

### Linux

- Kali Linux deployment
- Linux network configuration
- Linux file-system interaction
- Linux/Windows integration

### Cybersecurity

- Cybersecurity laboratory design
- Controlled security testing
- Security boundary definition
- CIA triad application
- Secure experimentation practices

### Documentation and Version Control

- Technical documentation
- Evidence management
- Git version control
- GitHub repository management
- Reproducible laboratory documentation

---

## 13. Git and Version Control

Git and GitHub were used to maintain the internship project documentation, provide version history and support traceability of changes.

The project repository is:

`https://github.com/rodmon/Cybersecurity-Lab`

The Week 1 report is maintained at:

`docs/WEEK-01-INTERNSHIP-REPORT.md`

Git GUI was used to manage the repository changes, stage the updated report, commit the changes and synchronize the updated documentation with GitHub.

The commit message used for the Week 1 report update was:

```text
docs: improve Week 1 internship report
```

This approach provides a documented and traceable history of changes made to the internship project.

---

## 14. Repository Structure

The cybersecurity laboratory is being documented using a structured repository layout.

```text
Cybersecurity-Lab/
│
├── README.md
│
├── docs/
│   ├── WEEK-01-INTERNSHIP-REPORT.md
│   ├── LAB-ARCHITECTURE.md
│   └── EVIDENCE-MATRIX.md
│
├── evidence/
│   └── week-01/
│       ├── 01-host-system.png
│       ├── 02-virtualbox.png
│       ├── 03-kali-vm.png
│       ├── 04-nat-network.png
│       ├── 05-kali-ip.png
│       ├── 06-connectivity.png
│       ├── 07-shared-folder.png
│       ├── 08-clipboard.png
│       └── 09-drag-drop.png
│
├── diagrams/
│   └── week-01-lab-topology.png
│
├── configuration/
│   └── network-configuration.md
│
└── CHANGELOG.md
```

---

## 15. Planned Next Steps

The laboratory established during Week 1 will serve as the foundation for subsequent cybersecurity practical activities.

Planned activities include:

1. Network reconnaissance
2. Host discovery
3. Service enumeration
4. Network scanning
5. Vulnerability assessment
6. Controlled penetration testing
7. Web application security testing
8. Network traffic analysis
9. Security monitoring
10. Incident response
11. Digital forensics
12. System hardening
13. Risk assessment
14. Security documentation

All activities will remain within authorized laboratory boundaries.

---

## 16. Outcome

At the end of Week 1, a functional cybersecurity testing laboratory had been successfully established.

The completed environment consists of:

```text
Windows 11 Host
       │
       ▼
Oracle VirtualBox
       │
       ▼
NAT Network
10.0.0.0/24
       │
       ▼
Kali Linux
10.0.0.2/24
       │
       ├── Internet Access
       ├── Clipboard Integration
       ├── Drag-and-Drop
       └── /downloads Shared Folder
```

The environment provides a controlled, reusable and expandable platform for practical cybersecurity training.

---

## 17. Professional and Security Relevance

The laboratory provides practical experience that is directly relevant to professional cybersecurity operations.

The skills developed during this phase include:

- Secure laboratory design
- Network segmentation concepts
- Virtual infrastructure management
- Linux administration
- Network configuration
- Security testing preparation
- Evidence management
- Version-controlled documentation
- Security boundary management
- Application of the CIA triad

These capabilities provide the technical foundation required for more advanced cybersecurity activities during the internship.

---

## 18. Conclusion

Week 1 successfully established the technical foundation required for the cybersecurity internship.

The deployment of Kali Linux within an Oracle VirtualBox environment, together with the `10.0.0.0/24` NAT Network and supporting host-integration features, provides a controlled platform for conducting authorized cybersecurity exercises.

The laboratory has been documented using Git and GitHub, with supporting architecture, configuration and evidence maintained separately to improve reproducibility, traceability and professional documentation standards.

The environment is now ready for the next phase of practical cybersecurity activities, including reconnaissance, enumeration, vulnerability assessment, penetration testing, monitoring, incident response and digital forensics.

---

## 19. Week 1 Summary

| **Area** | **Status** |
|---|---|
| Windows 11 Host | ✅ Completed |
| Oracle VirtualBox | ✅ Completed |
| Kali Linux Deployment | ✅ Completed |
| NAT Network | ✅ Completed |
| `10.0.0.0/24` Network | ✅ Completed |
| Kali `10.0.0.2/24` | ✅ Completed |
| Internet Connectivity | ✅ Completed |
| Clipboard Integration | ✅ Completed |
| Drag-and-Drop | ✅ Completed |
| `/downloads` Shared Folder | ✅ Completed |
| Laboratory Validation | ✅ Completed |
| Git Documentation | ✅ Completed |
| GitHub Repository | ✅ Completed |
| Foundation for Future Labs | ✅ Completed |

---

**End of Week 1 Internship Report**
