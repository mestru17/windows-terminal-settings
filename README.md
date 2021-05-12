# windows-terminal-settings
My Windows Terminal settings.

## Requirements
- [Delugia Nerd Font Complete](https://github.com/adam7/delugia-code)

## Installation
Download `settings.json` and put it in `C:\Users\{USERNAME}\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState` (overwrite the existing file if prompted), where `{USERNAME}` is the name of the system user.

I.e in a WSL terminal do (remember to replace `{USERNAME}`):
```bash
curl https://raw.githubusercontent.com/{USERNAME}/windows-terminal-settings/master/settings.json > settings.json
mv settings.json /mnt/c/Users/{USERNAME}/AppData/Local/Packages/Microsoft.WindowsTerminal_8wekyb3d8bbwe/LocalState
```

