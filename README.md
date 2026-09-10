# Cybersecurity Testing Lab – Week 1

**NetworkWalks Cybersecurity Internship | B083 | Week 1 | PM1**

A controlled cybersecurity testing laboratory designed and configured using **Windows 11, Oracle VirtualBox and Kali Linux**.
This project establishes the technical foundation for practical cybersecurity work, including network security, vulnerability assessment, penetration testing, security operations, incident response, digital forensics, risk assessment and cybersecurity best practices.

## Project Context

This repository documents my practical Week 1 internship work at **Networkwalks**, within the Cybersecurity Internship programme.
The internship scope includes exposure to network security, vulnerability assessment, penetration testing, security operations, incident response, digital forensics, risk assessment and cybersecurity best practices, together with hands-on training and real-world projects.

## Project Objective

The objective of Week 1 was to establish a controlled cybersecurity testing laboratory that can be used for authorised security testing, experimentation, validation and future practical cybersecurity exercises.

## Architecture
                         INTERNET
                            |
                            |
                    Windows 11 Host
                            |
                     Oracle VirtualBox
                            |
                    VirtualBox NAT Network
                       10.0.0.0/24
                            |
                            |
                     Kali Linux VM
                       10.0.0.2/24
                            |
                  Cybersecurity Testing
