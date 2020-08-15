---
title: Drive Letter and Volume Name
description: |
    Discover the last drive letter of the USB
    Device when it was plugged into the machine.
location: |
    XP:
    * Find ParentIdPrefix – SYSTEM\CurrentControlSet\Enum\USBSTOR
    * Using ParentIdPrefix Discover Last Mount Point
        – SYSTEM\MountedDevices

    Win7/8/10:
    * SOFTWARE\Microsoft\Windows Portable Devices\Devices
    * SYSTEM\MountedDevices
        - Examine Drive Letters looking at Value Data Looking for Serial Number
interpretation: |
    Identify the USB device that was last mapped
    to a specific drive letter. This technique will
    only work for the last drive mapped. It does
    not contain historical records of every drive
    letter mapped to a removable drive.
evids-categories:
  - externaldeviceusage
---
