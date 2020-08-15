---
title: Shell Bags
description: |
    Which folders were accessed on the local machine, the network,
    and/or removable devices. Evidence of previously existing
    folders after deletion/overwrite. When certain folders were
    accessed.
location: |
    Explorer Access:
    * USRCLASS.DAT\Local Settings\Software\Microsoft\Windows\Shell\Bags
    * USRCLASS.DAT\Local Settings\Software\Microsoft\Windows\Shell\BagMRU

    Desktop Access:
    * NTUSER.DAT\Software\Microsoft\Windows\Shell\BagMRU
    * NTUSER.DAT\Software\Microsoft\Windows\Shell\Bags
interpretation: |
    Stores information about which folders were most recently
    browsed by the user
evids-categories:
  - fileopening
---
