# SOC Lab with Azure & Sentinel

## Project Overview
In this lab, I built a cloud-based security monitoring environment using Azure and Microsoft Sentinel. The goal was to simulate a vulnerable environment, collect Windows security logs, and analyze them with Kusto Query Language (KQL) to detect suspicious activity.

## Key Achievements
- Successfully deployed a Windows 10 VM within a custom virtual network and intentionally exposed it to simulate a real-world attack surface.  
- Configured Azure Monitor Agent (AMA) to collect Windows Security Events, enabling centralized logging in Sentinel.  
- Created KQL queries to filter and visualize security events, including failed login attempts and privilege escalations, providing actionable insights.  
- Developed a Sentinel workbook with an interactive attack map to monitor activity in real time.

## Technical Skills Demonstrated
- Azure resource management: resource groups, virtual networks, and VMs.  
- Security monitoring with Sentinel and log analytics.  
- Log collection and analysis with AMA and KQL.  
- Simulating network vulnerabilities through firewall configuration.

## Process Summary
1. Provisioned a resource group and virtual network in Azure.  
2. Deployed a Windows 10 VM and configured a permissive firewall to simulate vulnerability.  
3. Disabled the VM firewall to test log collection.  
4. Created a Log Analytics workspace and integrated Sentinel.  
5. Imported the Windows Security Events solution from the Sentinel content hub.  
6. Configured data collection rules with AMA.  
7. Built Sentinel workbooks with custom KQL queries, including an interactive attack map for monitoring events.

## Outcome
This lab strengthened my ability to set up cloud-based security monitoring environments, collect and analyze logs, and visualize threats in Sentinel. It also reinforced best practices for simulating vulnerable networks and testing detection strategies.


_Ref 1_:Simulating Failed Logins w/ VPN
<img width="1918" height="527" alt="ref2" src="https://github.com/user-attachments/assets/8a03c882-3fca-4f04-a7c7-cd7e58a72e68" />
<img width="1650" height="933" alt="ref1" src="https://github.com/user-attachments/assets/3797d588-1a8a-42e1-95b4-365311af3d29" />











