# Virtual Security Incident Response Simulation

## Project Overview
This repository contains the deliverables for the **Week 2 Task: Virtual Security Incident Response Simulation**. The objective of this project is to simulate an incident response procedure within a controlled virtual environment, successfully detecting, containing, and recovering from a simulated security breach.

## Files Included
*   **Virtual_Security_Incident_Response_Report.docx**: The complete post-incident analysis report and incident response plan, documenting the lifecycle of the simulated breach.

## Methodology
The incident response plan was structured around the **NIST SP 800-61 Rev. 2 Incident Handling Guide**, encompassing:
1.  **Preparation:** Establishing baseline security and response capabilities.
2.  **Detection & Analysis:** Identifying Indicators of Compromise (IoCs) and root cause (simulated SQL injection leading to a reverse shell).
3.  **Containment, Eradication, & Recovery:** Isolating the affected web server, removing the malicious payload, patching the vulnerability, and safely restoring services.
4.  **Post-Incident Activity:** Analyzing the response effort and highlighting gaps in the initial security setup.

## Key Recommendations
The post-incident analysis generated the following critical recommendations to harden the infrastructure against future attacks:
*   Deployment of a Web Application Firewall (WAF).
*   Implementation of strict egress (outbound) network filtering.
*   Enabling File Integrity Monitoring (FIM) on critical application directories.