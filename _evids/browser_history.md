---
title: Browser History
description: |
    Records websites visited by date and time. Details stored
    for each local user account. Records number of times
    visited (frequency). Also tracks access of local system files
location: |
    Internet Explorer
        IE6-7:
        %USERPROFILE%\Local Settings\History\History.IE5
        
        IE8-9:
        %USERPROFILE%\AppData\Local\Microsoft\Windows\History\History.IE5
        
        IE10, 11, Edge:
        %USERPROFILE%\AppData\Local\Microsoft\Windows\WebCache\WebCacheV*.dat
    
    Firefox
        XP
        %USERPROFILE%\Application Data\Mozilla\Firefox\Profiles\<randomtext>.default\places.sqlite

        Win7/8/10
        %USERPROFILE%\AppData\Roaming\Mozilla\Firefox\Profiles\<random text>.default\places.sqlite

    Chrome
        XP
        %USERPROFILE%\Local Settings\Application Data\Google\Chrome\User Data\Default\History

        Win7/8/10
        %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\History
interpretation: |

evids-categories:
  - browserusage
---
