# remattmess

```
usage: remattmess [-h] [-d] message

REMove ATTachments from MESSage

positional arguments:
  message      message (file .eml or .msg) for remove

optional arguments:
  -h, --help   show this help message and exit
  -d, --debug  debug output
```
for multiple files:

    find . -type f  \( -name *.eml -o -name *.msg \) -exec remattmess {} \;

For python2:

    -#!/usr/bin/python3
    +#!/usr/bin/python2
    ...
    +from __future__ import print_function
    ...
    import os
    ...
