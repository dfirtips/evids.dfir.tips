---
title: Last-Visited MRU
description: |
    Tracks the specific executable used by an application to open the files documented in the `OpenSaveMRU` key. In addition, each value also tracks the directory location for the last file that was accessed by that application. Example: `Notepad.exe` was last run using the `C:\%USERPROFILE%\Desktop` folder
location: |
    XP:
    NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32\
    LastVisitedMRU

    Win7/8/10:
    NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32\
    LastVisitedPidlMRU
interpretation: |
    Tracks the application executables used to open files in
    OpenSaveMRU and the last file path used.
evids-categories:
  - programexecution
  - fileknowledge
  - fileopening
---
