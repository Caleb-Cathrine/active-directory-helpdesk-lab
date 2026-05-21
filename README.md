# Active Directory & Helpdesk Lab

Windows Server 2022 Domain Controller deployed on Microsoft Azure, with Active Directory administration and a simulated enterprise helpdesk using Zendesk.

📄 [View Full Documentation (PDF)](./CalebC_HelpDesk_Lab_Portfolio.pdf)

---

## What This Covers

- Deployed a Windows Server 2022 VM on Azure and promoted it to a Domain Controller
- Configured Active Directory Domain Services (AD DS) for the domain `CalebC.local`
- Joined a Windows 10 Enterprise client (Client-01) to the domain
- Created users, OUs, and security groups in Active Directory
- Set up a shared network drive (SMB) mapped to all domain clients as the Z: drive
- Simulated 4 real helpdesk ticket scenarios end-to-end using Zendesk

---

## Tech Stack

| Component | Details |
|---|---|
| Cloud | Microsoft Azure (Free Tier) |
| Server OS | Windows Server 2022 Datacenter |
| Client OS | Windows 10 Enterprise |
| Directory Service | Active Directory Domain Services |
| Domain | CalebC.local |
| Helpdesk | Zendesk |

---

## Ticket Scenarios

| Ticket | Type | Summary |
|---|---|---|
| #2 | Service Request | User cannot access shared network drive — mapped Z: drive via SMB |
| #3 | Incident (Urgent) | Account locked out — unlocked and reset password in AD |
| #4 | Service Request | Employee offboarding — disabled AD account on last day |
| #5 | Service Request | New hire onboarding — created AD account and added to Sales-Group |

---

## Certifications
- ✅ AZ-900 — Microsoft Azure Fundamentals
- 🔄 AZ-104 — Microsoft Azure Administrator *(in progress)*
