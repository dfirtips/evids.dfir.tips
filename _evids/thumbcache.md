---
title: Thumbcache
description: |
    Thumbnails of pictures, office documents, and folders exist in
    a database called the thumbcache. Each user will have their
    own database based on the thumbnail sizes viewed by the
    user (small, medium, large, and extra-larger
location: |
    C:\%USERPROFILE%\AppData\Local\Microsoft\Windows\Explorer
interpretation: |
    * These are created when a user switches a folder to
        thumbnail mode or views pictures via a slide show. As it
        were, our thumbs are now stored in separate database files.
        Win7+ has 4 sizes for thumbnails and the files in the cache
        folder reflect this:

        ```
        32 -> small - 96 -> medium
        256 -> large - 1024 -> extra large
        ```

    * The thumbcache will store the thumbnail copy of the picture
        based on the thumbnail size in the content of the equivalent
        database file. 
evids-categories:
  - fileknowledge
---
