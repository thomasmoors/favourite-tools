# Favourite tools
Tools I use every day (or at least a lot). Nothing shocking, but maybe there's something in here for you.


## Platform agnostic
 - [IDE's from Jetbrains](https://www.jetbrains.com/all/), like PhpStorm and Rider
 - [bitwarden](https://bitwarden.com/download/)
 - [dbeaver](https://dbeaver.io/download/)
 - [git](https://git-scm.com/downloads)
 - [ngrok](https://ngrok.com/download)
   - run as `ngrok http -region=eu 80` to make it use a European server
 - [postman](https://www.postman.com/downloads/)
 - [spotify](https://www.spotify.com/nl/download/windows/)
 - [vscode](https://code.visualstudio.com/download)
 - [docker](https://www.docker.com/products/docker-desktop)
 - [7zip](https://www.7-zip.org/download.html)
 - [neor profile SQL](https://www.profilesql.com/download/)

## Windows
 - [scoop](https://scoop.sh/)
   - install with `iwr -useb get.scoop.sh | iex` in PowerShell
   - tip: add this small script as `scoop_update.bat` to `%AppData%\Microsoft\Windows\Start Menu\Programs\Startup` to automatically update apps installed with scoop
 ```batch
scoop update *
scoop cache rm *
scoop cleanup *
exit
 ```
 - [cmder](https://github.com/cmderdev/cmder/releases/download/latest/cmder.zip)
   - If you install [AutoHotkey(https://www.autohotkey.com/download/ahk-install.exe) and add the following script as `home_dir.ahk`, you can use `~` for your home directory
   ```ahk
   #IfWinActive ahk_class VirtualConsoleClass
   ::~::C:\Users\[username]
   #IfWinActive
   ```
 - [laragon](https://github.com/leokhoa/laragon/releases/download/4.0.15/laragon-full.exe)
 - [windirstat](https://www.fosshub.com/WinDirStat.html?dwl=windirstat1_1_2_setup.exe)

## Mac
 - [iterm](https://iterm2.com/downloads.html)
 - [magnet](https://apps.apple.com/nl/app/magnet/id441258766?mt=12) / [veeer](https://veeer.io/) if you cannot miss the 9 dollar
 - [background music](https://github.com/kyleneideck/BackgroundMusic/releases)
 - [brew](https://brew.sh/)
   - install with `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
 
