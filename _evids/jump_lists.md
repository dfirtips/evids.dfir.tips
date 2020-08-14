---
title: Jump Lists
description: |
    * The Windows 7 task bar (Jump List) is engineered to allow
        users to “jump” or access items they have frequently or
        recently used quickly and easily. This functionality cannot
        only include recent media files; it must also include recent
        tasks.
    * The data stored in the AutomaticDestinations folder will
        each have a unique file prepended with the AppID of the
        associated application. 
location: |
    Win7/8/10:
    C:\%USERPROFILE%\AppData\Roaming\Microsoft\Windows\Recent\AutomaticDestinations
interpretation: |
    * First time of execution of application.
        * Creation Time = First time item added to the AppID file.
    * Last time of execution of application w/file open.
        * Modification Time = Last time item added to the AppID file.
    * List of Jump List IDs ->
        [LINK](http://www.forensicswiki.org/wiki/List_of_Jump_List_IDs)
evids-categories:
  - programexecution
  - fileopening
---
