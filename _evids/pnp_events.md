---
title: PNP Events
description: |
    When a Plug and Play driver install is
    attempted, the service will log an ID
    20001 event and provide a Status within
    the event. It is important to note that
    this event will trigger for any Plug and
    Play-capable device, including but not
    limited to USB, Firewire, and PCMCIA
    devices. 
location: |
    System Log File
    
        Win7/8/10:
        %system root%\System32\winevt\logs\System.evtx
interpretation: |
    * Event ID: 20001 – Plug and Play driver
        install attempted
        * Timestamp
        * Device information
        * Device serial number
        * Status (0 = no errors)
evids-categories:
  - externaldeviceusage
---
