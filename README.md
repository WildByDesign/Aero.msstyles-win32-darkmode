# Aero.msstyles-win32-darkmode
Aero.msstyles win32-darkmode toolbar button fix for Windows 11.

This Aero.msstyles theme is only a temporary workaround for users of Explorer++, Notepad++, LibreOffice and any other app that utilizes win32-darkmode and is affected by the blue-hinted toolbar button highlighting on Windows 11 only.

This is for users who still want the default Aero dark theme from Microsoft but with a fix for the toolbar button highlighting.

This is official Aero.msstyles from Windows 11 and the only modification is the one resource that is responsible for toolbar button highlighting.

This will not mess with your existing Aero theme or modify system files.

## Examples of the issue:

- https://github.com/notepad-plus-plus/notepad-plus-plus/issues/10510
- https://github.com/derceg/explorerplusplus/issues/115#issuecomment-1598660527
- https://bugs.documentfoundation.org/show_bug.cgi?id=152534

Usage:

- the archive needs to be extracted to: `C:\Windows\Resources\Themes`
- run the included `ThemeTool.exe` as Admin
- click Install to install the theme patcher
- restart your system
- run `ThemeTool.exe` again (you don't need Admin this time)
- select `aero11` theme and press Apply
