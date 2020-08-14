---
title: Recycle Bin (Win7/8/10)
description: |
    The recycle bin is a very important location on a Windows file
    system to understand. It can help you when accomplishing
    a forensic investigation, as every file that is deleted from a
    Windows recycle bin aware program is generally first put in
    the recycle bin. 
location: |
    Hidden System Folder

    Win7/8/10
    * C:\$Recycle.bin
    * Deleted Time and Original Filename contained in separate
      files for each deleted recovery file
interpretation: |
    * SID can be mapped to user via Registry Analysis
    * Win7/8/10
        - Files Preceded by `$I######` files contain
    * Original PATH and name
    * Deletion Date/Time
        - Files Preceded by `$R######` files contain
    * Recovery Data
evids-categories:
  - fileknowledge
---
