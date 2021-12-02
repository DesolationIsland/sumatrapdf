## sumatrapdf portable revise   
---
  For more information, take a look at this project: [sumatrapdf](https://github.com/sumatrapdfreader/sumatrapdf)

## I did
Added to the profile
|node|name|
|-----|----|
| root|computerName[string]|
|FileStates| IsRelativePath[bool], FileRelativePath[string] |
|SessionData->TabStates |IsRelativePath[bool], FileRelativePath[string]|
---
## Ideas
1. After execution, Record the name of the machine
2. Select a new file to determine the path. if it is a relative path. set "IsRelativePath" is true. moreover set "FileRelativePath".(Based on the relative path of the executable file)
3. Each time you start, decide whether to repair the path by comparing the machine names.Get the path to the executable file and repair the path according to "IsRelativePath" and "FileRelativePath".

## remarks
1.Copyright belongs to the original author
2.Provides a modification file,Compiled after replacement.
|path|filename|
|----|----|
|sumatrapdf\src|AppPrefs.cpp FileHistory.cpp FileHistory.h GlobalPrefs.cpp GlobalPrefs.h SettingsStructs.h|
|sumatrapdf\src\utils|WinUtil.cpp WinUtil.h|
----


