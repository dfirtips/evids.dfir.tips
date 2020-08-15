---
title: RDP Usage
description: |
    Track Remote Desktop Protocol logons to target machines
location: |
    Win7/8/10:
    %SYSTEM ROOT%\System32\winevt\logs\Security.evtx
interpretation: |
    * Win7/8/10 – Interpretation
        * Event ID 4778 – Session Connected/Reconnected
        * Event ID 4779 – Session Disconnected
    * Event log provides hostname and IP address of remote
        machine making the connection
    * On workstations you will often see current console session
        disconnected (4779) followed by RDP connection (4778)
evids-categories:
  - accountusage
---
