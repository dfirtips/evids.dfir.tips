---
title: Amcache.hve
description: |
    ProgramDataUpdater (a task associated with the Application
    Experience Service) uses the registry file Amcache.hve to store
    data during process creation
location: |
    Win7/8/10:
    C:\Windows\AppCompat\Programs\Amcache.hve
interpretation: |
    * Amcache.hve – Keys = **Amcache.hve\Root\File\{Volume GUID}\#######**
    * Entry for every executable run, full path information, File’s
        `$StandardInfo` Last Modification Time, and Disk volume the
        executable was run from
    * First Run Time = Last Modification Time of Key
    * SHA1 hash of executable also contained in the key 
evids-categories:
  - programexecution
---
