---
title: Network History
description: |
    * Identify networks that the computer has been connected to
    * Networks could be wireless or wired
    * Identify domain name/intranet name
    * Identify SSID
    * Identify Gateway MAC Address
location: |
    Win7/8/10 SOFTWARE HIVE:
    * SOFTWARE\Microsoft\Windows NT\CurrentVersion\NetworkList\Signatures\Unmanaged
    * SOFTWARE\Microsoft\Windows NT\CurrentVersion\NetworkList\Signatures\Managed
    * SOFTWARE\Microsoft\Windows NT\CurrentVersion\NetworkList\Nla\Cache
interpretation: |
    * Identifying intranets and networks that a computer has
    connected to is incredibly important
    * Not only can you determine the intranet name, you can
    determine the last time the network was connected to it based
    on the last write time of the key
    * This will also list any networks that have been connected to via
    a VPN
    * MAC Address of SSID for Gateway could be physically triangulated
evids-categories:
  - networkactivity
---
