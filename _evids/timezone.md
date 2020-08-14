---
title: Timezone
description: |
    Identifies the current system time zone.
location: |
    SYSTEM Hive:
    SYSTEM\CurrentControlSet\Control\TimeZoneInformation
interpretation: |
    * Time activity is incredibly useful for correlation of activity
    * Internal log files and date/timestamps will be based on the
        system time zone information
    * You might have other network devices and you will need to
        correlate information to the time zone information collected here.
evids-categories:
  - networkactivity
---
