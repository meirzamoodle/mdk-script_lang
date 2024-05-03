# mdk-script_lang

# How to install:
1. Put the `commands/lang.py` to where the original code of mdk python is installed. for example: `/home/you/.local/lib/python3.10/site-packages/mdk/commands`
2. Edit the `commands/__init__.py` and add `'lang'` to the commandsList list, you can put it after `'js'`.
3. Done

# How to use:
## Add new string identifier
`mdk lang add newstringid -d "the newstringid description" lang.php`

## Sort the existing string identifiers in a file
`mdk lang sort lang.php`
