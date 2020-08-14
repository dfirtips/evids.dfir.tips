---
title: WLAN Event Logs
description: |
    Determine what wireless networks the system associated with and
    identify network characteristics to find location

    Relevant Event IDs
    
    * 11000 – Wireless network association started
    * 8001 – Successful connection to wireless network
    * 8002 – Failed connection to wireless network
    * 8003 – Disconnect from wireless network
    * 6100 – Network diagnostics (System log)
location: |
    Microsoft-Windows-WLAN-AutoConfig Operational.evtx
interpretation: |
    * Shows historical record of wireless network connections
    * Contains SSID and BSSID (MAC address), which can be used to
        geolocate wireless access point *(no BSSID on Win8+)
evids-categories:
  - networkactivity
---
