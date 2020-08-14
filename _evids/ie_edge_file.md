---
title: IE|Edge file://
description: |
    A little-known fact about the IE History is that the information
    stored in the history files is not just related to Internet
    browsing. The history also records local and remote (via
    network shares) file access, giving us an excellent means for
    determining which files and applications were accessed on
    the system, day by day. 
location: |
    Internet Explorer:

        IE6-7
        %USERPROFILE%\LocalSettings\History\History.IE5

        IE8-9
        %USERPROFILE%\AppData\Local\Microsoft\WindowsHistory\History.IE5

        IE10-11
        %USERPROFILE%\AppData\Local\Microsoft\Windows\WebCache\WebCacheV*.dat
interpretation: |
    * Stored in `index.dat` as: `file:///C:/directory/filename.ext`
    * Does not mean file was opened in browser
evids-categories:
  - fileknowledge
  - fileopening
---
