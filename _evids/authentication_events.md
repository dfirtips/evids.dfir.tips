---
title: Authentication Events
description: |
    Authentication mechanism
location: |
    Recorded on system that authenticated credentials
    Local Account/Workgroup = on workstation
    Domain/Active Directory = on domain controller

    Win7/8/10:
    %SYSTEM ROOT%\System32\winevt\logs\Security.evtx
interpretation: |
    * Event ID Codes (NTLM protocol)
        * 4776: Successful/Failed account authentication

    * Event ID Codes (Kerberos protocol)
        * 4768: Ticket Granting Ticket was granted (successful logon)
        * 4769: Service Ticket requested (access to server resource)
        * 4771: Pre-authentication failed (failed logon)
evids-categories:
  - accountusage
---
