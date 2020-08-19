# vscode_hotkeys_and_settings
Cheat sheet of hotkeys and setting of my VSCode.

## Hotkeys

* Close left panel : `cmd` + `b`
* Switch between file tabs : `ctrl` + `tab`
* Move to next file tab : `ctrl` + `page down`
* Move to previous file tab: `ctrl` + `page up`

* Switch to the left (1st) pane (editor groups) : `cmd` + `1`
* Switch to the right(2nd) pane (editor groups) : `cmd` + `2`

* Move to the left pane (self defined binding) : `cmd` + `h`
* Move to the right pane (self defined binding) : `cmd` + `j`

* Circle through opening files (left ward) : `cmd` + `shift` + `[`
* Circle through opening files (right ward) : `cmd` + `shift` + `]`

* Preview Markdown: `cmd` + `k` then press v

* Upload VSCode settings to gist : `shift` + `opt` + `u`
* Download VSCode settings to gist : `shift` + `opt` + `d`

* Go to definition : `F12`

* Go to previous location (on Mac):  `ctrl` + `-`
* Go to previous location (on Linux) : `ctrl` + `alt` + `-`
  

Depending on the OS, the user settings file is located here:

Windows `%APPDATA%\Code\User\settings.json`
macOS `$HOME/Library/Application Support/Code/User/settings.json`
Linux `$HOME/.config/Code/User/settings.json`


The `Settings Sync` plugin of VSCode has uploaded the follow json file to Github gist.

* `cloudSettings`
* `extensions.json`
* `keybindings.json`
* `keybindingsMac.json`
* `settings.json`

[2020-07-07] Changes made in the settings

* fontSize: changed to 16 in settings.json
* lineHeight: changed to 19 in settings.json
* added hotkey `cmd` + `h` in `keybindingsMac.json` 
* added hotkey `cmd` + `j` in `keybindingsMac.json` 

[2020-08-19] Setup VSCode on Ubuntu 18.04

1) Download VSCode `.deb` file from [Link](https://code.visualstudio.com/docs/setup/linux)
2) Install the `.deb` file, either through Package Manager GUI or `sudo apt install .deb`
3) Launch VSCode and install `Settings Sync` plugin.
4) Authorize Github account in `Settings Sync` plugin.
5) Key on `Ctrl + Alt + D` on Linux or `Ctrl + Opt + D` on Mac remoted Linux to download the VScode Gist configurations.
6) The Gist will install all other plugins and setup VSCode configurations.
