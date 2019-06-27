PHPExcel
========

The PHPExcel module allows developers to export/import data to/from Excel files.

The idea behind this module is to have a single module for handling the export or
import of Excel files, instead of multiple modules handling specific cases.

The module provides no functionality as-is (the .module file is as good as empty).
The phpexcel.inc file must be included to use the export or import functions
in your own module:
```php
module_load_include('inc', 'phpexcel');
```


Installation
------------

Install this module using the official Backdrop CMS instructions at
https://backdropcms.org/guide/modules


API reference
-------------

See this: phpexcel.api.php


Library
-------

PHPExcel's library is included under 'libraries' folder.
Details: https://github.com/PHPOffice/PHPExcel


Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/phpexcel/issues


Current Maintainers
-------------------

- Attila Vasas (https://github.com/vasasa).


Credits
-------

- Ported to Backdrop CMS by Attila Vasas (https://github.com/vasasa).
- Originally written for Drupal by Wouter Admiraal (https://www.drupal.org/u/wadmiraal).


License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
