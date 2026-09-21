# Hi, I'm Abhinay Batchu 👋

### IT Support | Service Desk | IAM | Active Directory | Microsoft 365 | Windows | Networking

I'm an **IT Support professional based in Toronto, Canada**, with hands-on experience supporting users in an enterprise education environment and a technical background in Computer Science and Cybersecurity.

During my IT Technician internship, I supported users across multiple campus locations through **Jira, phone, and chat**, assisting with Windows troubleshooting, Microsoft 365 applications, user access and authentication issues, hardware and software problems, network connectivity, ticket documentation, and incident escalation.

I enjoy troubleshooting technical issues systematically—understanding the symptoms, identifying the cause, applying an appropriate solution, validating that normal service has been restored, and documenting or escalating the issue when required.

My current technical focus is **Windows administration, Active Directory, Microsoft 365, identity and access management, networking, PowerShell, IT service management, and enterprise IT support**.

---

## 🛠️ Technical Skills

<table>
<tr>
<td valign="top" width="33%">

### 💻 IT Support & Windows

- Windows 10/11
- Windows Server
- Windows Administration
- Desktop & Endpoint Support
- Hardware & Software Troubleshooting
- Printer & Peripheral Support
- Software Installation
- Remote User Support
- Windows Services & Processes
- Event Viewer

</td>
<td valign="top" width="33%">

### 🔐 Microsoft & Identity

- Microsoft 365
- Outlook, Teams & OneDrive
- Active Directory
- Microsoft Entra ID
- Identity & Access Management (IAM)
- Intune Fundamentals
- Authentication & MFA
- Conditional Access
- User & Group Administration
- Access Control & Least Privilege
- Hybrid Identity

</td>
<td valign="top" width="33%">

### 🌐 Networking

- TCP/IP
- IPv4 Addressing & Subnetting
- DNS & DHCP
- ARP
- LAN/WAN
- Wi-Fi & Ethernet
- VPN
- Routing & Default Gateways
- TCP/UDP & Common Ports
- Network Connectivity Troubleshooting
- Wireshark Packet Analysis

</td>
</tr>

<tr>
<td valign="top">

### 🎫 ITSM & Support

- Jira
- ServiceNow
- Incident Management
- Service Requests
- Ticket Triage & Categorization
- Impact & Urgency Assessment
- Ticket Prioritization
- SLA Awareness
- Ticket Documentation
- Customer Communication
- Escalation & Handoff

</td>
<td valign="top">

### ⚙️ Administration & Tools

- PowerShell
- Command Prompt
- VMware Workstation
- Git & GitHub
- Visual Studio Code
- Linux

</td>
<td valign="top">

### 🛡️ Support Practices

- Structured Troubleshooting
- Technical Validation
- End-User Support
- User Account Troubleshooting
- Access Administration
- Endpoint Troubleshooting
- Network Troubleshooting
- Least-Privilege Administration
- Technical Documentation
- Incident Escalation

</td>
</tr>
</table>

---

# 🧪 IT Support Lab Series

A five-project hands-on portfolio focused on practical **enterprise IT Support, Service Desk, identity, endpoint, Microsoft 365, networking, troubleshooting, and support operations**.

Each project includes technical documentation, troubleshooting evidence, screenshots, validation procedures, and real-world support scenarios.

---

## Project 1 — Active Directory IT Support Home Lab

Built a multi-VM Windows enterprise environment to practice **IT Support, Service Desk, identity administration, access control, and troubleshooting workflows**.

### Lab Environment

```text
VMware Workstation
        |
        +--- DC01 — Windows Server 2025
        |       AD DS | DNS | File Shares
        |
        +--- DC02 — Windows Server 2025
        |       AD DS | DNS | Global Catalog
        |
        +--- CLIENT01 — Windows 11
                Domain-Joined Workstation
```

### What I Implemented

- Deployed Active Directory Domain Services and DNS
- Built an enterprise-style Organizational Unit structure
- Created and administered domain users and security groups
- Implemented AGDLP-based resource authorization
- Joined a Windows 11 workstation to the domain
- Configured and validated Group Policy
- Configured departmental SMB and NTFS permissions
- Implemented Group Policy drive mapping
- Added a second domain controller and validated AD replication
- Implemented redundant Active Directory DNS
- Delegated Help Desk password-reset permissions using least privilege
- Troubleshot domain authentication and account lockouts
- Investigated Windows Security events including `4625`, `4740`, and `4724`
- Simulated employee onboarding and offboarding
- Troubleshot Active Directory replication using `repadmin` and `dcdiag`
- Performed final end-to-end environment validation

### Key Technologies

`Windows Server 2025` · `Windows 11` · `Active Directory` · `DNS` · `Group Policy` · `PowerShell` · `SMB` · `NTFS` · `RSAT` · `VMware Workstation`

➡️ **[View the Active Directory IT Support Home Lab](https://github.com/abhinaybatchu/active-directory-it-support-lab)**

---

## Project 2 — Microsoft 365, Entra ID & Hybrid Identity IT Support Lab

Built a hands-on Microsoft 365 and Microsoft Entra ID enterprise environment focused on **IT Support, cloud identity administration, access management, troubleshooting, and hybrid identity**.

### Lab Environment

```text
On-Premises Active Directory
        |
        +--- DC01 / DC02 — Windows Server 2025
        |       AD DS | DNS | Users | Groups
        |
        +--- SYNC01 — Microsoft Entra Connect
        |       Password Hash Synchronization
        |       Controlled User Synchronization
        |
        +--- CLIENT01 — Windows 11
        |       AD Domain-Joined
        |
        +--- CLOUDCLIENT01 — Windows 11
                Microsoft Entra Joined

Microsoft Cloud
        |
        +--- Microsoft Entra ID
        |       Users | Security Groups | Roles
        |       MFA | Conditional Access
        |       Sign-In Logs | Audit Logs
        |
        +--- Microsoft 365
                Exchange Online
                Microsoft Teams
                SharePoint Online
                OneDrive
```

### What I Implemented

- Created and administered Microsoft Entra ID users and security groups
- Managed Microsoft 365 licensing and service provisioning
- Administered Exchange Online, Teams, SharePoint, and OneDrive
- Configured RBAC and least-privilege administrative access
- Investigated Microsoft Entra sign-in and audit logs
- Tested Conditional Access with MFA in Report-only mode
- Used Microsoft Graph PowerShell for cloud administration
- Integrated on-premises Active Directory with Microsoft Entra ID using Entra Connect
- Configured Password Hash Synchronization
- Scoped hybrid synchronization to a controlled pilot group
- Troubleshot licensing, access, authentication, and synchronization issues
- Resolved a privileged-account hybrid identity matching issue
- Practiced Joiner, Mover, and Leaver workflows

### Key Technologies

`Microsoft 365` · `Microsoft Entra ID` · `Active Directory` · `Entra Connect` · `Exchange Online` · `Teams` · `SharePoint` · `OneDrive` · `Conditional Access` · `MFA` · `RBAC` · `Microsoft Graph PowerShell` · `Hybrid Identity`

➡️ **[View the Microsoft 365, Entra ID & Hybrid Identity IT Support Lab](https://github.com/abhinaybatchu/microsoft-365-entra-it-support-lab)**

---

## Project 3 — Windows Endpoint Administration & PowerShell Lab

Built a Windows 11 endpoint administration and troubleshooting lab focused on common **IT Support, desktop support, system administration, and PowerShell automation** responsibilities.

### What I Implemented

- Administered local users, groups, permissions, and UAC
- Configured and validated NTFS permissions
- Investigated Windows processes, services, and startup behavior
- Troubleshot applications and Windows services
- Reviewed software, storage, and device information
- Worked with Windows Update, Microsoft Defender, and Windows Firewall
- Used Event Viewer and Reliability Monitor for troubleshooting
- Used PowerShell for endpoint administration and diagnostics
- Built a PowerShell endpoint health-check script
- Investigated and restored a stopped Print Spooler service
- Performed technical validation after remediation
- Documented a Help Desk-style endpoint troubleshooting scenario

### Key Technologies

`Windows 11` · `PowerShell` · `Windows Administration` · `NTFS` · `Windows Services` · `Event Viewer` · `Reliability Monitor` · `Microsoft Defender` · `Windows Firewall` · `Endpoint Troubleshooting`

➡️ **[View the Windows Endpoint Administration & PowerShell Lab](https://github.com/abhinaybatchu/windows-endpoint-powershell-it-support-lab)**

---

## Project 4 — Enterprise Networking Troubleshooting Lab

Built a hands-on Windows enterprise networking lab focused on **TCP/IP, DNS, connectivity troubleshooting, service validation, and packet analysis**.

### Lab Environment

```text
                   Gateway
                192.168.170.2
                      |
          +-----------+-----------+
          |                       |
      CLIENT01                   DC01
   192.168.170.20          192.168.170.10
                                  |
                                DC02
                          192.168.170.11
```

### What I Implemented

- Investigated IPv4 addressing, subnet masks, and network configuration
- Simulated and diagnosed an incorrect subnet configuration
- Investigated static addressing and DHCP concepts
- Troubleshot Active Directory DNS resolution
- Simulated a DNS client misconfiguration and restored service
- Inspected ARP and IP-to-MAC address resolution
- Analyzed local and remote routing behavior
- Investigated default gateway and WAN connectivity
- Tested TCP service connectivity using PowerShell
- Reviewed Windows Firewall profiles and network connections
- Used Windows networking tools for structured diagnostics
- Captured and analyzed ICMP, DNS, and SMB-related traffic with Wireshark
- Completed a Help Desk/NOC-style DNS incident scenario
- Validated DNS resolution and TCP/445 service connectivity after remediation

### Key Technologies

`TCP/IP` · `IPv4` · `DNS` · `DHCP` · `ARP` · `Routing` · `TCP/UDP` · `Windows Firewall` · `PowerShell` · `Wireshark` · `Network Troubleshooting`

➡️ **[View the Enterprise Networking Troubleshooting Lab](https://github.com/abhinaybatchu/enterprise-networking-troubleshooting-lab)**

---

## Project 5 — IT Service Desk Incident Simulation Lab

Built an end-to-end Service Desk simulation covering common enterprise **incidents, service requests, ticket prioritization, troubleshooting, validation, communication, and escalation workflows**.

### What I Implemented

- Created structured incident and service-request tickets
- Categorized tickets by issue type and affected service
- Assessed user impact and urgency
- Assigned priorities using a simplified support model
- Applied SLA awareness when evaluating the ticket queue
- Investigated an Active Directory account lockout
- Fulfilled an approved Finance access request
- Troubleshot and restored the Windows Print Spooler service
- Investigated and restarted a Windows application process
- Reviewed Microsoft Entra ID sign-in activity
- Investigated and remediated an internal DNS connectivity issue
- Validated service connectivity after remediation
- Identified a simulated multi-user shared-service incident
- Documented troubleshooting already performed before escalation
- Created an escalation handoff for an Infrastructure/Application team
- Prioritized a multi-ticket Service Desk queue
- Practiced customer communication and closure workflow awareness
- Performed technical validation without claiming unsupported user-level confirmation

### Support Workflow

```text
Ticket Intake
     ↓
Categorize
     ↓
Assess Impact & Urgency
     ↓
Prioritize / Consider SLA
     ↓
Investigate
     ↓
Remediate
     ↓
Technical Validation
     ↓
User Confirmation Where Applicable
     ↓
Document
     ↓
Close or Escalate
```

### Key Technologies & Skills

`ITSM` · `Service Desk` · `Incident Management` · `Service Requests` · `SLA Awareness` · `Active Directory` · `Microsoft Entra ID` · `Windows 11` · `PowerShell` · `DNS` · `TCP/IP` · `Troubleshooting` · `Technical Validation` · `Customer Communication` · `Escalation`

➡️ **[View the IT Service Desk Incident Simulation Lab](https://github.com/abhinaybatchu/it-service-desk-incident-simulation-lab)**

---

## 📜 Certifications

- **Google IT Support Professional Certificate**
- **Google Cybersecurity Professional Certificate**
- **Help Desk Technician — ServiceDesk Simulator**

---

## 🎓 Education

**Postgraduate Program in Cybersecurity**  
Sault College of Applied Arts and Technology

**Bachelor of Science — Mathematics / Statistics / Computer Science**  
Osmania University

My cybersecurity education complements my IT Support background with knowledge of **identity and access management, secure administration, access control, networking, endpoint security, and security-conscious troubleshooting**.

---

## 🎯 Professional Focus

I'm continuing to strengthen my practical skills across:

- Windows administration and endpoint support
- Active Directory
- Microsoft 365 and Microsoft Entra ID
- Identity and access management
- PowerShell
- Enterprise networking
- IT service management
- Technical troubleshooting
- Incident handling and escalation

I'm currently pursuing opportunities including:

- **IT Support Technician**
- **Service Desk Analyst**
- **IT Support Analyst**
- **IT Specialist**
- **Technical Support Specialist**
- **Help Desk Technician**
- **IAM Analyst / Identity Support**

---

## 🤝 Connect With Me

📍 Toronto, Ontario, Canada

💼 **[LinkedIn](https://www.linkedin.com/in/abhinaybatchu/)**

---

> **Learn. Practice. Document. Improve.**
