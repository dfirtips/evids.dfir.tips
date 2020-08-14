---
title: ADS Zone.Identifier
evids-categories:
  filedownload:
    - description: |
        Starting with XP SP2 when files are downloaded from the “Internet Zone”
        via a browser to a NTFS volume, an alternate data stream is added to the
        file. The alternate data stream is named “Zone.Identifier.” 
      interpretation: |
        Files with an ADS Zone.Identifier and contains ZoneID=3 were downloaded
        from the Internet
        * URLZONE_TRUSTED = ZoneID = 2
        * URLZONE_INTERNET = ZoneID = 3
        * URLZONE_UNTRUSTED = ZoneID = 4
---
