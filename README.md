# The-Windows
#AutoIt3Wrapper_UseX64=y $sFile = ("C:\WINDOWS\system32\SnippingTool.exe") If FileExists($sFile) Then    ;ShellExecute($sFile)     run($sFile) Else    MsgBox(0,'File Error', "The Windows snipping tool was not found") EndIf
