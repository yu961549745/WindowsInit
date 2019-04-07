# 在此处打开 conda

在文件夹空白处右键有效
```
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\Directory\Background\shell\conda]
@="conda here"
"Icon"="C:\\ProgramData\\Anaconda3\\python.exe"

[HKEY_CLASSES_ROOT\Directory\Background\shell\conda\command]
@="cmd.exe /K C:\\ProgramData\\Anaconda3\\Scripts\\activate.bat"

```