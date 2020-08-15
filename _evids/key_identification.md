---
title: Key Identification
description: |
    Track USB devices plugged into a machine. 
location: |
    SYSTEM\CurrentControlSet\Enum\USBSTOR
    SYSTEM\CurrentControlSet\Enum\USB
interpretation: |
    * Identify vendor, product, and version of a USB device
        plugged into a machine
    * Identify a unique USB device plugged into the machine
    * Determine the time a device was plugged into the
        machine
    * Devices that do not have a unique serial number will
        have an `&` in the second character of the serial number. 
evids-categories:
  - externaldeviceusage
---
