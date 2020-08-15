---
title: Open/Save MRU
description: |
  In the simplest terms, this key tracks files that have been opened or
  saved within a Windows shell dialog box. This happens to be a big data
  set, not only including web browsers like Internet Explorer and Firefox,
  but also a majority of commonly used applications.
location: |
  XP:
  NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32\OpenSaveMRU

  Win7/8/10:
  NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32\OpenSavePIDlMRU
interpretation:
  - '**The “*” key** – This subkey tracks the most recent files of any extension input in an OpenSave dialog'
  - '**.??? (Three letter extension)** – This subkey stores file info from the OpenSave dialog by specific extension'
evids-categories:
  - filedownload
  - fileopening
---
