**WEEK 1 INTERNSHIP PROJECT REPORT**

**Project Title:** *Design and Setup of a Cybersecurity Testing Laboratory Environment Using VirtualBox and Kali Linux*

**1. Internship Context**

This project forms part of my Cybersecurity Internship at Networkwalks. The internship provides practical exposure to network security, vulnerability assessment, penetration testing, security operations, incident response, digital forensics, risk assessment and cybersecurity best practices, together with hands-on training and real-world projects.
Week 1 focused on establishing the controlled technical environment required for subsequent cybersecurity exercises.

**2. Introduction**

During the first week of the internship, I worked on setting up a controlled cybersecurity testing laboratory on a Windows 11 laptop.

The laboratory was designed using Oracle VirtualBox as the virtualization platform, with Kali Linux deployed as the primary cybersecurity testing machine.

The purpose of the environment is to provide an isolated and controlled platform in which cybersecurity concepts, network security techniques, vulnerability assessment, penetration testing and related security activities can be practiced without directly affecting production infrastructure.

**3. Objectives**

The objectives of Week 1 were to:
1.	Establish a functional cybersecurity testing laboratory. 
2.	Configure VirtualBox as the virtualization platform. 
3.	Deploy Kali Linux as the cybersecurity testing machine. 
4.	Configure an isolated laboratory network. 
5.	Use the 10.0.0.0/24 network. 
6.	Configure Kali Linux with 10.0.0.2/24. 
7.	Provide Internet connectivity for legitimate updates and security research. 
8.	Enable controlled clipboard and file drag-and-drop functionality. 
9.	Configure the /downloads shared folder. 
10.	Establish a reusable environment for future cybersecurity practical exercises. 

**4. Technologies and Tools**

**Technology/Tool**	         **Purpose**

1. Windows 11	              = Host operating system
2. Oracle VirtualBox          =	Virtualization platform
3. Kali Linux	              = Cybersecurity testing machine
4. NAT Network	              = Virtual network connectivity
5. IPv4	                      = Network addressing
6. 10.0.0.0/24	              = Laboratory network
7. Shared Folder	          = Controlled file exchange
8. Clipboard Integration	  = Host/VM text exchange

**6. Laboratory Network Design**

The laboratory uses a VirtualBox NAT Network with the 10.0.0.0/24 subnet.
Kali Linux was configured with the address 10.0.0.2/24.

INTERNET
    |
Windows 11 Host
    |
Oracle VirtualBox
    |
NAT Network
10.0.0.0/24
    |
Kali Linux VM
10.0.0.2/24
    |
Security Testing Lab

The design provides a structured environment that can later be expanded with additional virtual machines representing servers, workstations, vulnerable targets, monitoring systems and other security components.

**7. Virtual Machine Configuration**

Kali Linux was deployed as the primary cybersecurity testing virtual machine.
The configuration included:
•	Kali Linux virtual machine deployment. 
•	NAT Network connectivity. 
•	10.0.0.0/24 laboratory subnet. 
•	Kali Linux address 10.0.0.2/24. 
•	Internet connectivity. 
•	Clipboard integration. 
•	File drag-and-drop. 
•	Shared /downloads directory. 

**8. File Sharing and Host Integration**

A shared /downloads folder was configured to support controlled transfer of files between the Windows host and Kali Linux virtual machine.

Clipboard and drag-and-drop functionality were also enabled to support practical administration and laboratory workflow.
These facilities are intended for controlled transfer of legitimate tools, scripts, documentation and other resources required for authorized exercises.

**9. Validation**

The Week 1 environment was validated through the available configuration and connectivity evidence.
Evidence is maintained in: https://github.com/rodmon/Cybersecurity-Lab/tree/week-01 or
evidence/week-01/ 
The evidence matrix maps each screenshot to the corresponding activity, skill and security relevance.

**10. Security Considerations**

The laboratory was designed as a controlled environment for cybersecurity learning and practical experimentation.
Future scanning, enumeration, vulnerability assessment, exploitation and related security testing will be restricted to authorized laboratory systems or other explicitly authorized targets.
The design supports the confidentiality, integrity and availability principles of the CIA triad by establishing defined testing boundaries and avoiding unnecessary interaction with production systems.

**11. Work Completed**

The following activities were completed during Week 1:
1.	Defined requirements for the cybersecurity laboratory. 
2.	Prepared the Windows 11 host environment. 
3.	Selected VirtualBox as the virtualization platform. 
4.	Deployed Kali Linux. 
5.	Configured the VirtualBox NAT Network. 
6.	Established the 10.0.0.0/24 laboratory subnet. 
7.	Configured Kali Linux with 10.0.0.2/24. 
8.	Enabled Internet connectivity. 
9.	Enabled clipboard integration. 
10.	Enabled file drag-and-drop. 
11.	Configured the /downloads shared folder. 
12.	Established the foundation for subsequent cybersecurity testing.
    
**11. Outcome**

At the end of Week 1, a functional cybersecurity testing laboratory had been established.
The environment provides a dedicated Kali Linux testing machine and a structured virtual network that can be expanded for future cybersecurity exercises.

**12. Skills Demonstrated**

The Week 1 activity demonstrates practical exposure to:
•	Virtualization 
•	Windows host administration 
•	Linux deployment 
•	Kali Linux administration 
•	IPv4 networking 
•	NAT networking 
•	Network configuration 
•	Connectivity validation 
•	Cybersecurity laboratory design 
•	Controlled security testing 
•	Documentation and evidence management 

**13. Planned Next Steps**

The next stages of the project will build on this laboratory by introducing practical cybersecurity activities in subsequent tasks such as:
•	Network reconnaissance 
•	Host discovery 
•	Service enumeration 
•	Vulnerability assessment 
•	Controlled penetration testing 
•	Web application security testing 
•	Network traffic analysis 
•	Security monitoring 
•	Incident response 
•	Digital forensics 
•	System hardening 
•	Risk assessment 

**14. Conclusion**

Week 1 established the technical foundation required for practical cybersecurity work during the internship.
The completed VirtualBox and Kali Linux environment provides a controlled platform for future security testing and validation activities.
The project is documented as a reproducible technical portfolio with separate evidence, architecture, configuration and reporting documentation.



