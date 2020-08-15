---
title: Office Recent Files
description: |
    MS Office programs will track their own Recent Files list to make
    it easier for users to remember the last file they were editing.
location: |
    NTUSER.DAT\Software\Microsoft\Office\VERSION
    * 14.0 = Office 2010        * 11.0 = Office 2003
    * 12.0 = Office 2007        * 10.0 = Office XP

    NTUSER.DAT\Software\Microsoft\Office\VERSION\UserMRU\LiveID_####\FileMRU
    * 15.0 = Office 365
interpretation: |
    Similar to the Recent Files, this will track the last files that were
    opened by each MS Office application. The last entry added, per
    the MRU, will be the time the last file was opened by a specific
    MS Office application.
evids-categories:
  - fileopening
---
