---
title: Recent Files
description: |
    Registry Key that will track the last files and folders opened and
    is used to populate data in “Recent” menus of the Start menu.
location: |
    NTUSER.DAT:
    NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\RecentDocs
interpretation: |
    * **RecentDocs** – Overall key will track the overall order of the
        last 150 files or folders opened. MRU list will keep track of the
        temporal order in which each file/folder was opened. The last
        entry and modification time of this key will be the time and
        location the last file of a specific extension was opened.
    * **.???** – This subkey stores the last files with a specific extension
        that were opened. MRU list will keep track of the temporal
        order in which each file was opened. The last entry and
        modification time of this key will be the time when and location
        where the last file of a specific extension was opened.
    * **Folder** – This subkey stores the last folders that were opened.
        MRU list will keep track of the temporal order in which each
        folder was opened. The last entry and modification time of this
        key will be the time and location of the last folder opened.
evids-categories:
  - fileopening
---
