---
title: Unique USB (User)
description: |
    Find User that used the Unique USB Device. 
location: |
    * Look for GUID from SYSTEM\MountedDevices
    * NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\MountPoints2
interpretation: |
    This GUID will be used next to identify the user that
    plugged in the device. The last write time of this key
    also corresponds to the last time the device was
    plugged into the machine by that user. The number
    will be referenced in the user’s personal mountpoints
    key in the `NTUSER.DAT` Hive
evids-categories:
  - externaldeviceusage
---
