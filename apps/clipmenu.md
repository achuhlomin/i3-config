## Clipmenu

- [clipmenu](https://github.com/cdown/clipmenu)

### Setup

    # Systemd
    systemctl --user enable clipmenud
    systemctl --user start clipmenud

    # i3
    bindsym $alt+Ctrl+v exec --no-startup-id CM_LAUNCHER=rofi clipmenu