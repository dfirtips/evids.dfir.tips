---
title: Session Restore
description: |
    Automatic Crash Recovery features built into the browser
location: |
    Internet Explorer
        Win7/8/10
        %USERPROFILE%/AppData/Local/Microsoft/Internet Explorer/Recovery
    
    Firefox
        Win7/8/10
        %USERPROFILE%\AppData\Roaming\Mozilla\Firefox\Profiles\<randomtext>.default\sessionstore.js

    Chrome
    
        Win7/8/10
        %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\
    
        Files = Current Session, Current Tabs, Last Session, Last Tabs
interpretation: |
    * Historical websites viewed in each tab
    * Referring websites
    * Time session ended
    * Modified time of `.dat` files in `LastActive` folder
    * Time each tab opened (only when crash occurred)
    * Creation time of `.dat` files in `Active` folder
evids-categories:
  - browserusage
---
