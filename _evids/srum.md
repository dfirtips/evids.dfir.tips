---
title: System Resource Usage Monitor (SRUM)
description: |
    Records 30 to 60 days of historical system performance.
    Applications run, user account responsible for each, and
    application and bytes sent/received per application per hour
location: |
    SOFTWARE\Microsoft\WindowsNT\CurrentVersion\SRUM\Extensions {d10ca2fe-6fcf4f6d-848e-b2e99266fa89} = Application Resource Usage Provider C:\Windows\System32\SRU\ 
interpretation: |
    Use tool such as `srum_dump.exe` to cross correlate the data
    between the registry keys and the SRUM ESE Database. 
evids-categories:
  - programexecution
  - networkactivity
---
