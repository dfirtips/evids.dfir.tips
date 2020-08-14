---
title: Browser Download Manager
evids-categories:
  filedownload:
    - description: |
        Firefox and IE has a built-in download manager application which keeps
        a history of every file downloaded by the user. This browser artifact can
        provide excellent information about what sites a user has been visiting
        and what kinds of files they have been downloading from them. 
      location: |
        Firefox:

            XP:
            %userprofile%\Application Data\Mozilla\ Firefox\Profiles\<random text>.default\downloads.sqlite

            Win7/8/10:
            %userprofile%\AppData\Roaming\Mozilla\ Firefox\Profiles\<random text>.default\downloads.sqlite
        
        Internet Explorer:
        
            IE8-9:
            %USERPROFILE%\AppData\Roaming\Microsoft\Windows\ IEDownloadHistory\
            
            IE10-11:
            %USERPROFILE%\AppData\Local\Microsoft\Windows\WebCache\ WebCacheV*.dat
      interpretation: |
        Downloads will include:
        * Filename, Size, and Type
        * Download from and Referring Page
        * File Save Location
        * Application Used to Open File
        * Download Start and End Times
---
