---
title: Browser Artifacts
evids-categories:
  filedownload:
    - description: |
        Not directly related to “File Download”. Details stored for each local user
        account. Records number of times visited (frequency). 
      location: |
        Internet Explorer

            IE8-9:
            %USERPROFILE%\AppData\Roaming\Microsoft\Windows\IEDownloadHistory\index.dat

            IE10-11:
            %USERPROFILE%\AppData\Local\Microsoft\Windows\WebCache\WebCacheV*.dat

        Firefox

            v3-25:
            %userprofile%\AppData\Roaming\Mozilla\ Firefox\Profiles\<random text>.default\downloads.sqlite

            v26+:
            %userprofile%\AppData\Roaming\Mozilla\ Firefox\Profiles\<random text>.default\places.sqlite
            Table:moz_annos

        Chrome:

            Win7/8/10:
            %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\History
      interpretation: |
        Many sites in history will list the files that were opened from remote
        sites and downloaded to the local system. History will record the access
        to the file on the website that was accessed via a link.
---
