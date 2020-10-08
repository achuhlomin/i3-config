## i3

- [config](i3_config) `~/.i3/config`  
- [keyboard languages](gxkb.cfg) `~/.config/gxkb/gxkb.cfg `  
- pulseaudio `/etc/pulse/daemon.conf`      
- lock and exit config `/usr/bin/i3exit`  
- status bars  
    + [i3blocks](i3blocks_config) `~/.config/i3blocks/config`
    + [i3status](i3status_config) `~/.config/i3status/config`    
    
### Additional utils

- Look&Feel can be changed with `lxappearance`.
- For wallpaper selection use `nitrogen`.
- Notifications are managed with `dunst`.
- `xprop | awk '/WM_CLASS/ { print $4 }'` to get application window class
- `conky` desktop widgets (/usr/share/conky)

### Status bars

- `i3status` is default bar
- `i3blocks` is rich for features so one is recommended

#### i3status (default)

~/.i3/config

    ...
    bar {
        ...
    	status_command i3status
    }
    
~/.config/i3status/config

#### i3blocks (recommended)

~/.i3/config

    ...
    bar {
        ...
    	status_command i3blocks
    }
    
~/.config/i3blocks/config

[see more on github.com/vivien/i3blocks](https://github.com/vivien/i3blocks)