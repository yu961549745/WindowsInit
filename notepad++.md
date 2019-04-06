# Notepad++ 自定义添加右键菜单

```
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\*\shell\Notepad++]
@="Open with Notepad++"
"Icon"="C:\\Program Files\\Notepad++\\notepad++.exe"

[HKEY_CLASSES_ROOT\*\shell\Notepad++\command]
@="\"C:\\Program Files\\Notepad++\\notepad++.exe\" \"%1\""

```