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

To set Clink directories for script
```
clink installscripts DIR
```