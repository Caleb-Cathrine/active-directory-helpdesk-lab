Active Directory & Helpdesk Lab
Windows Server 2022 Domain Controller deployed on Microsoft Azure, with Active Directory administration and a simulated enterprise helpdesk using Zendesk.
📄 View Full Documentation (PDF)

What This Covers

Deployed a Windows Server 2022 VM on Azure and promoted it to a Domain Controller
Configured Active Directory Domain Services (AD DS) for the domain CalebC.local
Joined a Windows 10 Enterprise client (Client-01) to the domain
Created users, OUs, and security groups in Active Directory
Set up a shared network drive (SMB) mapped to all domain clients as the Z: drive
Simulated 4 real helpdesk ticket scenarios end-to-end using Zendesk


Tech Stack
ComponentDetailsCloudMicrosoft Azure (Free Tier)Server OSWindows Server 2022 DatacenterClient OSWindows 10 EnterpriseDirectory ServiceActive Directory Domain ServicesDomainCalebC.localHelpdeskZendesk

Ticket Scenarios
TicketTypeSummary#2Service RequestUser cannot access shared network drive — mapped Z: drive via SMB#3Incident (Urgent)Account locked out — unlocked and reset password in AD#4Service RequestEmployee offboarding — disabled AD account on last day#5Service RequestNew hire onboarding — created AD account and added to Sales-Group
