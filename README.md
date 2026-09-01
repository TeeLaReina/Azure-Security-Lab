# Azure Security Lab

A hands-on Azure security engineering project built to demonstrate practical 
knowledge across identity, network, compute, storage, threat detection, and AI 
security - aligned to the AZ-500 and SC-500 certification curricula.

## What This Is

A structured 20-day lab environment where each day implements a distinct security 
control or architecture pattern in Microsoft Azure. Every configuration is documented 
with screenshots, decision rationale, and security reasoning - built to show not just 
*what* was configured, but *why*.

## What This Covers

- Identity, Access & Governance (PIM, Conditional Access, Managed Identities, Entra Agent ID)
- Network Security (Azure Firewall, NSGs, ASGs, Private Endpoints, WAF)
- Compute & Storage Security (Disk Encryption, Storage Hardening, SQL Security)
- Container Security (ACR, ACI, Defender for Containers)
- Threat Modeling (Microsoft Threat Modeling Tool, STRIDE)
- Defender for Cloud (CSPM, Secure Score, Workload Protection Plans)
- Microsoft Sentinel (SIEM and SOAR - data connectors, KQL detections, playbooks)
- AI Security (Defender for AI, Entra Agent ID, Purview DSPM for AI, Security Copilot)
- Python Automation (Azure SDK, Managed Identity authentication)

## Exam Alignment

| Exam | Coverage |
|---|---|
| SC-500 - Microsoft Cybersecurity Architect | Full curriculum |
| AZ-500 - Azure Security Technologies | Full curriculum |

## Structure

Each `day-XX/` folder contains:
- `README.md` - what was built, the security reasoning behind it, and what was learned
- Screenshots demonstrating configurations and key concepts
- Scripts, KQL queries, ARM/Bicep templates, or playbook exports where produced

## Skills Demonstrated

`Azure RBAC` `Privileged Identity Management` `Conditional Access` `Managed Identities`
`Azure Firewall` `Network Security Groups` `Private Link` `Web Application Firewall`
`Azure Key Vault` `Disk Encryption` `Azure Policy` `Defender for Cloud`
`Microsoft Sentinel` `KQL` `SOAR Playbooks` `Threat Modeling` `Container Security`
`AI Security` `Python` `Infrastructure as Code`
