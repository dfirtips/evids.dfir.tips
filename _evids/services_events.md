---
title: Services Events
description: |
    * Analyze logs for suspicious services running at boot time
    * Review services started or stopped around the time of a
        suspected compromise
location: |
    All Event IDs reference the System Log

        7034 – Service crashed unexpectedly
        7035 – Service sent a Start/Stop control
        7036 – Service started or stopped
        7040 – Start type changed (Boot | On Request | Disabled)
        7045 – A service was installed on the system (Win2008R2+)

        4697 – A service was installed on the system (from Security log)
interpretation: |
    * All Event IDs except 4697 reference the System Log
    * A large amount of malware and worms in the wild utilize
        Services
    * Services started on boot illustrate persistence (desirable in
        malware)
    * Services can crash due to attacks like process injection
evids-categories:
  - accountusage
---
