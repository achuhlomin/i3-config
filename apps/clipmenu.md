## Clipmenu

- [clipmenu](https://github.com/cdown/clipmenu)

### Set up clipmenud

    clipmenud -h

    # Run clipmenud as service
    systemctl --user enable clipmenud
    systemctl --user start clipmenud

    # Set up clipmenud unit
    systemctl --user edit clipmenud
    # Add only following lines these overrite/add lines in original unit
        [Service]
        Environment="CM_SELECTIONS=clipboard"
    systemctl --user restart clipmenud

### Set up clipmenu

    clipmenu -h

    # i3
    bindsym $alt+Ctrl+v exec --no-startup-id CM_LAUNCHER=rofi CM_HISTLENGTH=30 clipmenu -p 'clipboard'