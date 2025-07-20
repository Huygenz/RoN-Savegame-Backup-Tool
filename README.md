# RoN-Savegame-Backup-Tool
A savegame backup tool for Ready or Not

![Ready or Not Logo](https://cdn2.steamgriddb.com/logo_thumb/0b94ce08688c6389ce7b68c52ce3f8c7.png)

...when you want to play safe in Commander Mode.

To use the script:
1. Put the LSPDSM.ps1 into  new folder
2. Create a .bat file in the same location as the .ps1 script with the following content:

    @echo off

    start "" powershell.exe -NoProfile -ExecutionPolicy Bypass -WindowStyle Hidden -File ".\LSPDSM.ps1"

    exit
4. You can now create a shortcut to that .bat file for more simple handling (also the shortcut can have an icon)
5. Doubleclick the shortcut

The tool itself is quite simple:
Press "Backup Now!" to save a new backup. Do that after a successful run, after loading into in the police department or main menu.
Press "Restore Now!" to overwrite your in-game saves. Do that while in Main Menu or LSPD hub.
Press "Options" to change your path where to backup will be stored.
Press "Exit" to exit.
