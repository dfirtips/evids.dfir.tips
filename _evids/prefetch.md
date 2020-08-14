---
title: Prefetch
description: |
    * Increases performance of a system by pre-loading code
        pages of commonly used applications. Cache Manager
        monitors all files and directories referenced for each
        application or process and maps them into a .pf file. Utilized
        to know an application was executed on a system.
    * Limited to 128 files on XP and Win7
    * Limited to 1024 files on Win8
    * `(exename)-(hash).pf`
location: |
    WinXP/7/8/10:
    C:\Windows\Prefetch
interpretation: |
    1) Program Execution

    * Each .pf will include last time of execution, number of times
        run, and device and file handles used by the program
    * Date/Time file by that name and path was first executed
        * Creation Date of .pf file (-10 seconds)
    * Date/Time file by that name and path was last executed
        * Embedded last execution time of .pf file
        * Last modification date of .pf file (-10 seconds)
        * Win8-10 will contain last 8 times of execution
    
    2) File/Folder Opening

    * Can examine each .pf file to look for file handles recently used
    * Can examine each .pf file to look for device handles recently used
evids-categories:
  - programexecution
  - fileopening
---
