---
title: Browser Search Terms
description: |
    Records websites visited by date and time. Details stored for each
    local user account. Records number of times visited (frequency).
    Also tracks access of local system files. This will also include the
    website history of search terms in search engines.
location: |
    Internet Explorer

        * IE6-7:
        %USERPROFILE%\Local Settings\History\History.IE5
        
        * IE8-9:
        %USERPROFILE%\AppData\Local\Microsoft\Windows\History\History.IE5
        
        * IE10-11:
        %USERPROFILE%\AppData\Local\Microsoft\Windows\WebCache\WebCacheV*.dat
    
    Firefox
    
        * XP:
        %userprofile%\Application Data\Mozilla\Firefox\Profiles\<randomtext>.default\places.
        sqlite
        
        * Win7/8/10:
        %userprofile%\AppData\Roaming\Mozilla\Firefox\
        Profiles\<randomtext>.default\places.sqlite
interpretation: |

evids-categories:
  - networkactivity
---
