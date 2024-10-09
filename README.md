# AD-SOC-Home-Lab

This lab integrates Active Directory with a SOC using Splunk, focusing on AD management, log analysis, and threat detection. It includes simulated attacks to practice monitoring and incident response, providing hands-on experience in cybersecurity operations.

## Objective

The objective of this project is to create a home lab that integrates an Active Directory (AD) environment with a Security Operations Center (SOC) using Splunk. This lab aims to simulate real-world enterprise scenarios, focusing on AD administration, centralized log management, and threat detection. The setup will allow for hands-on experience in monitoring, detecting, and responding to security incidents, while also practicing incident response workflows and SOC operations.

## Overview

![SOC-proj drawio](https://github.com/user-attachments/assets/e8cf505b-e4f0-43af-ac2a-ac2ba1fba636)

*Ref 1: Network Diagram*

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- **Windows Server:** For setting up the Active Directory Domain Controller.
- **Windows 11:** As client machines joined to the AD domain.
- **Splunk:** For centralized log management, monitoring, and threat detection.
- **Sysmon (System Monitor):** For detailed logging of processes, network connections, and more.
- **Splunk Universal Forwarder:** For forwarding Windows logs to Splunk.
- **Kali Linux:** For simulating attacks against the AD environment.
- **Oracle VirtualBox/VMware Workstation:** For virtualizing the entire lab environment.
- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Environment Setup
Register an account at <a href="https://idp.login.splunk.com/signin/register">Splunk</a> <br>
Download and install <a href="https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html">Oracle VM VirtualBox</a> 

- Local Operating System: `Windows` Workstation or any Linux OS.
- Security Monitoring: We will install `Sysmon` on both of the Windows instances for detailed system activity logging.
- Log Forwarding: We will install `Splunk Universal Forwarder` on both of the Windows instances for log forwarding.
- Log Analysis: We will utilize `Ubuntu Server` to host `Splunk Server`.
- Active Directory: One of the Windows servers will serve as our `Active Directory` domain controller. Install and configure Active Directory Domain Services on this server.

 ## Installation

