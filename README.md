# Apple-Scripts

## Services
This is saved under `~/Library/Services`

`batman/grayscale` -- Control-Option-Command-G

`globalgrayscale` -- Control-G

`Open-Preview` -- Option-Shift-Command-G

`Open-Safari` -- Control-Option-Command-G

'Open-Anki' -- Control-Option-Shift-Command-Space

## Karabiner Keybindings
This is saved under `~/.config/karabiner`

## Launchd
This is saved under `~/Library/LaunchAgents`

`/Library/LaunchDaemons` - Put your plist scripts in this folder if your job needs to run even when no users are logged in.

`/Library/LaunchAgents` - Put your plist scripts in this folder if the job is only useful when users are logged in. (this has the side-effect of your job being run as 'root' after a system reboot.)

`$HOME/Library/LaunchAgents` - Put your plist files in this folder if the job is only useful when users are logged in. (When your plist configuration file is placed here, your job will be run under your username.)
