## Enpass

[Enpass looks too small or big on my display](https://www.enpass.io/support/kb/troubleshooting/enpass-looks-too-small-or-big-on-my-display-how-can-i-fix-it/)

    # ~/.profile
    export QT_AUTO_SCREEN_SCALE_FACTOR=0
    export QT_SCREEN_SCALE_FACTORS=1

### Change icon

[Change icon](https://github.com/awesomeWM/awesome/issues/2742)

    sudo mv /usr/share/icons/hicolor/48x48/status/enpass-status.png /usr/share/icons/hicolor/48x48/status/enpass-status.png.backup
    sudo mv /usr/share/icons/hicolor/44x44/status/enpass-status.png /usr/share/icons/hicolor/44x44/status/enpass-status.png.backup
    sudo mv /usr/share/icons/hicolor/32x32/status/enpass-status.png /usr/share/icons/hicolor/32x32/status/enpass-status.png.backup
    sudo mv /usr/share/icons/hicolor/24x24/status/enpass-status.png /usr/share/icons/hicolor/24x24/status/enpass-status.png.backup
    sudo mv /usr/share/icons/hicolor/22x22/status/enpass-status.png /usr/share/icons/hicolor/22x22/status/enpass-status.png.backup
    sudo mv /usr/share/icons/hicolor/16x16/status/enpass-status.png /usr/share/icons/hicolor/16x16/status/enpass-status.png.backup