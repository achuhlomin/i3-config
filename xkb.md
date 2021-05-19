## Xkb

### Variant 1: setxkbmap

    setxkbmap -layout us,ru -option grp:caps_toggle
    sbxkb

### Variant 2: gxkb (gxkb.cfg)

    [xkb config]
    group_policy=2
    default_group=0
    never_modify_config=false
    model=pc105
    layouts=us,ru
    variants=,
    toggle_option=grp:caps_toggle
    compose_key_position=