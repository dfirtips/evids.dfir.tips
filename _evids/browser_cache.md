---
title: Browser Cache
description: |
    * The cache is where web page components can be stored
        locally to speed up subsequent visits
    * Gives the investigator a “snapshot in time” of what a
        user was looking at online
        - Identifies websites which were visited
        - Provides the actual files the user viewed on a given
            website
        - Cached files are tied to a specific local user account
        - Timestamps show when the site was first saved and last
            viewed
location: |
    Internet Explorer
        
        IE8-9
        %USERPROFILE%\AppData\Local\Microsoft\Windows\Temporary Internet Files\Content.IE5
        
        IE10
        %USERPROFILE%\AppData\Local\Microsoft\Windows\Temporary Internet Files\Content.IE5
        
        IE11
        %USERPROFILE%\AppData\Local\Microsoft\Windows\INetCache\IE
        
        Edge
        %USERPROFILE%\AppData\Local\Packages\microsoft.microsoftedge_<APPID>\AC\MicrosoftEdge\Cache
    
    Firefox
        XP
        %USERPROFILE%\Local Settings\ApplicationData\Mozilla\Firefox\Profiles\
        <randomtext>.default\Cache
        
        Win7/8/10
        %USERPROFILE%\AppData\Local\Mozilla\Firefox\Profiles\
        <randomtext>.default\Cache
    
    Chrome
        XP
        %USERPROFILE%\Local Settings\Application Data\Google\Chrome\User Data\Default\Cache
        - data_# and f_######
        
        Win7/8/10
        %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\Cache\ 
        - data_# and f_######
interpretation: |

evids-categories:
  - browserusage
---
