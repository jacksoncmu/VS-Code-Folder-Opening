# VS Code Context Menu Integration

This project adds a **"Open with VS Code"** option to the Windows right-click context menu.  
It allows you to quickly open files or folders in [Visual Studio Code](https://code.visualstudio.com/) directly from File Explorer.

This is done via a Windows Registry script (`.reg`) script. 

## Installation
1. Locate your Visual Studio Code installation path. The script is set up for `D:\Microsoft VS Code\Code.exe` by default, so update the path if yours is different.
2. Save the `test.txt` script file with UTF-16 LE encoding.
3. Rename the file extension from .txt to .reg and double-click it to apply.