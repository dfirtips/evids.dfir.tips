---
title: First/Last Times
description: |
    Determine temporal usage of specific USB devices
    connected to a Windows Machine. 
location: |
    First Time
        Plug and Play Log Files

        XP:
        C:\Windows\setupapi.log

        Win7/8/10:
        C:\Windows\inf\setupapi.dev.log

    ---

    First, Last, and Removal Times
    (Win7/8/10 Only)
    
        System Hive:
        \CurrentControlSet\Enum\USBSTOR\Ven_Prod_Version\USBSerial#\Properties\
        {83da6326-97a6-4088-9453-a19231573b29}\####

        0064 = First Install (Win7-10)
        0066 = Last Connected (Win8-10)
        0067 = Last Removal (Win8-10)
interpretation: |
    * Search for Device Serial Number
    * Log File times are set to local time zone 
evids-categories:
  - externaldeviceusage
---
