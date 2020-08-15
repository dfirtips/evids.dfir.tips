---
title: Logon Types
description: |
    Logon Events can give us very specific information regarding
    the nature of account authorizations on a system if we know
    where to look and how to decipher the data that we find. In
    addition to telling us the date, time, username, hostname, and
    success/failure status of a logon, Logon Events also enables us
    to determine by exactly what means a logon was attempted. 
location: |
    Win7/8/10:
    Event ID 4624
interpretation: |
    | Logon | Type Explanation |
    |:---:|:--- |
    | 2 | Logon via console |
    | 3 | Network Logon |
    | 4 | Batch Logon |
    | 5 | Windows Service Logon |
    | 7 | Credentials used to unlock screen |
    | 8 | Network logon sending credentials (cleartext) |
    | 9 | Different credentials used than logged on user |
    | 10 | Remote interactive logon (RDP) |
    | 11 | Cached credentials used to logon |
    | 12 | Cached remote interactive (similar to Type 10) |
    | 13 | Cached unlock (similar to Type 7) |
evids-categories:
  - accountusage
---
