S3 File System Migrate
======================

This module integrates with the S3 File System (S3FS) module (version 2.x). S3FS enables storing newly uploaded and generated files on 
Amazon's Simple Storage Service. S3FS Migrate allows migrating existing locally stored files to S3. S3FS Migrate has the following features:

- Configurable via a user-friendly UI.
- Can migrate all files in the Public and/or Private file systems, or just files for individual file or image fields.
- Provides statistics about migration progress.
- Files are migrated incrementally via cron.
- The site does not need to be put into maintenance mode.
- If a file could not be migrated then it is still accessible from its original location, and migration will be attempted in the next pass, 
  after all remaining files have been migrated.
- Backups of every migrated file can optionally be stored in a special folder in the private file system.

Installation
------------
Install this module using the official Backdrop CMS instructions
at https://docs.backdropcms.org/documentation/extend-with-modules.

Differences from Drupal 7
-------------------------

- Should work the same as Drupal 7.

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/s3fs_migrate/issues).

Current Maintainers
-------------------

- [Justin Keiser](https://github.com/keiserjb).

Credits 
-------

- Ported to Backdrop CMS by [Justin Keiser](https://github.com/keiserjb).
- Originally written for Drupal by [Oliver Coleman](https://github.com/OliverColeman).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.



