## Xrandr

### [Autorandr](https://github.com/phillipberndt/autorandr)

    # Save your current display configuration and setup with:
    $ autorandr --save mobile

    # Connect an additional display, configure your setup and save it:
    $ autorandr --save docked-nvidia

    # Now autorandr can detect which hardware setup is active:
    $ autorandr
    mobile
    docked (detected)

    # To automatically reload your setup:
    $ autorandr --change

    # To manually load a profile:
    $ autorandr --load <profile>
    # or simply:
    $ autorandr <profile>

    # autorandr tries to avoid reloading an identical configuration. To force the (re)configuration:
    $ autorandr --load <profile> --force
