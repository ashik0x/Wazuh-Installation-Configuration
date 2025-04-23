# Wazuh Installation & Configuration for Windows Monitoring
Implemented and configured the Wazuh Security Information and Event Management (SIEM) solution to  monitor a Windows system for security threats.  • Installed and configured Wazuh Manager for centralized log collection and analysis.  • Deployed the Wazuh Agent on a Windows system to enable real-time monitoring and threat detection.

## Overview

Wazuh is an open-source Security Information and Event Management (SIEM) tool that provides threat detection, integrity monitoring, incident response, and compliance. In this project, I deployed and configured a complete Wazuh stack and connected it to a Windows host for monitoring.

## Objectives

- Implement centralized log collection and analysis using Wazuh Manager.
- Deploy Wazuh Agent on a Windows system.
- Monitor and detect suspicious activity in real-time.

## Tools & Technologies

- *Wazuh OVA (Manager + Dashboard)*
- *Windows 10/11 System*
- *VirtualBox*
- *Wireshark, Nmap (for traffic analysis)*

## Installation Steps

### 1. Wazuh Manager Setup
- Imported the Wazuh OVA file into VirtualBox.
- Configured network settings (Host-only adapter + NAT).
- Accessed the Wazuh dashboard through the browser.

### 2. Windows Agent Deployment
- Downloaded and installed the Wazuh Agent.
- Registered the agent with the Wazuh Manager using agent-auth.
- Verified successful connection and real-time log forwarding.

### 3. Threat Detection and Alerting
- Simulated attacks and observed alert logs.
- Example: Triggered alerts using failed login attempts

## Sample Screenshot

![Wazuh Dashboard](![IMG-20250423-WA0004](https://github.com/user-attachments/assets/516a14c9-ee29-400f-ba1a-93e7671f834c)



## Sample Wazuh Alert dashboard
![IMG-20250423-WA0003](https://github.com/user-attachments/assets/6cfe65a9-9f81-47ca-8276-3ac3516e1803)
