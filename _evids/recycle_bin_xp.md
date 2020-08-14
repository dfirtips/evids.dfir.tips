---
title: Recycle Bin (WinXP)
description: |
    The recycle bin is a very important location on a Windows file
    system to understand. It can help you when accomplishing
    a forensic investigation, as every file that is deleted from a
    Windows recycle bin aware program is generally first put in
    the recycle bin. 
location: |
    Hidden System Folder

    Windows XP
    * C:\RECYCLER” 2000/NT/XP/2003
    * Subfolder is created with user’s SID
    * Hidden file in directory called “INFO2”
    * INFO2 Contains Deleted Time and Original Filename
    * Filename in both ASCII and UNICODE
interpretation: |
    * SID can be mapped to user via Registry Analysis
    * Maps file name to the actual name and path it was deleted from
evids-categories:
  - fileknowledge
---
