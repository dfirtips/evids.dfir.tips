---
title: RecentApps
description: |
  GUI Program execution launched on the Win10 system is
  tracked in the RecentApps key
location: |
  Win10:
  NTUSER.DAT\Software\Microsoft\Windows\Current Version\Search\RecentApps
interpretation: |
  Each GUID key points to a recent application.
  AppID = Name of Application
  LastAccessTime = Last execution time in UTC
  LaunchCount = Number of times executed
evids-categories:
  - programexecution
---
