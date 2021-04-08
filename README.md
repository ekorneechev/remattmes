# remattmess

```usage: remattmess [-h] [-d] message

REMove ATTachments from MESSage

positional arguments:
  message      message (file .eml or .msg) for remove

optional arguments:
  -h, --help   show this help message and exit
  -d, --debug  debug output
```
for multiple files:

    find . -type f  \( -name *.eml -o -name *.msg \) -exec remattmess {} \;
