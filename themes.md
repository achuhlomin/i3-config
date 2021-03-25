## Themes

### Bpytop

    ls -la /usr/share/bpytop/themes/
    
    # ~/.config/bpytop/bpytop.conf
    color_theme="matcha-dark-sea"

### Rofi

[Rofi Themes](https://github.com/davatorium/rofi/tree/next/themes)

    rofi -combi-modi window,drun -show combi -modi combi -theme solarized_alternate

### Kitty

[Kitty Themes](https://github.com/dexpota/kitty-themes)

    # ~/.config/kitty/kitty.conf
    include ./theme.conf
    
    rm ~/.config/kitty/theme.conf
    ln -s ~/.config/kitty/kitty-themes/themes/Grape.conf ~/.config/kitty/theme.conf