# Clink

## Install

Add the following to Windows Terminal settings.json
```
{
    "colorScheme": "One Half Dark",
    "commandline": "%SystemRoot%\\System32\\cmd.exe /s /k \"C:\\git\\terminal_conf\\clink\\clink_x64.exe inject --profile C:\\git\\terminal_conf\\profile\"",
    "font": 
    {
        "face": "CaskaydiaCove Nerd Font Mono"
    },
    "guid": "{6d765724-f16b-47d1-9e76-60051d01d354}",
    "hidden": false,
    "icon": "C:\\git\\terminal_conf\\clink\\clink.ico",
    "name": "PowerTerminal",
    "opacity": 100,
    "startingDirectory": "%USERPROFILE%"
},
```

Install scripts
```
git clone https://github.com/shunsambongi/clink-zoxide.git
git clone https://github.com/chrisant996/clink-gizmos.git
git clone https://github.com/vladimir-kotikov/clink-completions.git

clink installscripts clink_completions
clink installscripts clink-gizmos
clink installscripts clink-zoxide
```