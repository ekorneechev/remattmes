# remattmess

Version: 0.6

```
usage: remattmess [-h] [-d] [-u] [-v] [FILE]

REMove ATTachments from MESSage

positional arguments:
  FILE           message (file .eml or .msg) for remove

options:
  -h, --help     show this help message and exit
  -d, --debug    debug output
  -u, --update   update script
  -v, --version  show version
```
for multiple files:

    find . -type f  \( -name *.eml -o -name *.msg \) -exec remattmess {} \;

For python2 (2.6 and above) use remattmess.py2 (usage: remattmess message)
