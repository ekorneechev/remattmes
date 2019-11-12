# remattmess
REMove ATTachments from MESSage

Usage (The file is not backuped! Yet.):

    remattmess <message_file>

for multiple files:

    find . -type f  \( -name *.eml -o -name *.msg \) -exec remattmess {} \;
