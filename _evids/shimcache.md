---
title: Shimcache
description: |
  * Windows Application Compatibility Database is used by
    Windows to identify possible application compatibility
    challenges with executables.
  * Tracks the executables file name, file size, last modified time,
    and in Windows XP the last update time 
location: |
  XP:
  SYSTEM\CurrentControlSet\Control\SessionManager\AppCompatibility

  Win7/8/10:
  SYSTEM\CurrentControlSet\Control\Session Manager\AppCompatCache
interpretation: |
  Any executable run on the Windows system could be found
  in this key. You can use this key to identify systems that
  specific malware was executed on. In addition, based on the
  interpretation of the time-based data you might be able to
  determine the last time of execution or activity on the system.
  * Windows XP contains at most 96 entries
    * LastUpdateTime is updated when the files are executed
  * Windows 7 contains at most 1,024 entries
    * LastUpdateTime does not exist on Win7 systems
evids-categories:
  - programexecution
---
