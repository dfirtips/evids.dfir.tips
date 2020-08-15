---
title: Volume Serial Number
description: |
    Discover the Volume Serial Number of
    the Filesystem Partition on the USB.
    (NOTE: This is not the USB Unique Serial
    Number, which is hardcoded into the
    device firmware.)
location: |
    * SOFTWARE\Microsoft\WindowsNT\CurrentVersion\ENDMgmt

    * Use Volume Name and USB Unique Serial Number to:
        - Find last integer number in line
        - Convert Decimal Serial Number into Hex Serial Number
interpretation: |
    * Knowing both the Volume Serial
        Number and the Volume Name,
        you can correlate the data across
        `SHORTCUT File (LNK)` analysis and the
        `RECENTDOCs` key.
    * The Shortcut File (LNK) contains the
        Volume Serial Number and Name
    * `RecentDocs` Registry Key, in most
        cases, will contain the volume name
        when the USB device is opened via
        Explorer
evids-categories:
  - externaldeviceusage
---
