---
title: UserAssist
evids-categories:
  programexecution:
    - description: |
        GUI-based programs launched from the desktop are tracked in
        the launcher on a Windows System
      location: |
        NTUSER.DAT HIVE:
        NTUSER.DAT\Software\Microsoft\Windows\Currentversion\Explorer\UserAssist\{GUID}\Count
      interpretation: |
        All values are ROT-13 Encoded
        * GUID for XP
          * 75048700 Active Desktop
        * GUID for Win7/8/10
          * CEBFF5CD Executable File Execution
          * F4E57C4B Shortcut File Execution
---
