# dotfiles
dotfiles and configs for heron laptop  
running ArchLinux (btw) with sway WM, no DE  
Using [Dracula Theme](https://draculatheme.com/) wherever possible for a consistent look.

## what it currently looks like
![preview](./preview.png)

## The Packages
- [alacritty](https://github.com/alacritty/alacritty) - Terminal emulator
- brightnessctl - Monitor brightness control
- [cava](https://aur.archlinux.org/packages/cava/) (AUR) - CLI audio visualizer
- [font-awesome](https://archlinux.org/packages/community/any/font-awesome/) - Fancy icons - [Icon Picker](https://fontawesome.com/v5.15/icons?d=gallery&p=2&m=free)
- [grim](https://github.com/emersion/grim) - Image grabber
- [grimshot](https://aur.archlinux.org/packages/grimshot/) (AUR) - Better screenshot handling
- feh - image viewer
- [mako](https://github.com/emersion/mako) - notifications
- pavucontrol - PulseAudio Volume Control
- playerctl - enable media controls keys
- [sway](https://github.com/swaywm/sway)
- [swaylock-effects](https://github.com/mortie/swaylock-effects) - Better lockscreen
- [wal](https://github.com/dylanaraps/wal) (AUR) - Colorscheme templates
- [waybar](https://github.com/Alexays/Waybar)
- [wofi](https://hg.sr.ht/~scoopta/wofi) - dmenu replacement

## symlinks used
*(This needs a proper cleanup and an automated script at some point.)*
```
ln -s ~/git/dotfiles/alacritty/alacritty.yml ~/.config/alacritty/alacritty.yml
ln -s ~/git/dotfiles/alacritty/dracula.yml ~/.config/alacritty/dracula.yml
ln -s ~/git/dotfiles/bashtop/user_themes/dracula.theme ~/.config/bashtop/user_themes/dracula.theme
ln -s ~/git/dotfiles/cava/config ~/.config/cava/config
ln -s ~/git/dotfiles/gtk-3.0/settings.ini ~/.config/gtk-3.0/settings.ini
ln -s ~/git/dotfiles/mako/config ~/.config/mako/config
ln -s ~/git/dotfiles/neofetch/config.conf ~/.config/neofetch/config.conf
ln -s ~/git/dotfiles/nwg-launchers/nwgbar/style.css ~/.config/nwg-launchers/nwgbar/style.css
ln -s ~/git/dotfiles/nwg-launchers/nwgbar/bar.json ~/.config/nwg-launchers/nwgbar/bar.json
ln -s ~/git/dotfiles/sway/config ~/.config/sway/config
ln -s ~/git/dotfiles/sway/sway.d/10-general.conf ~/.config/sway/sway.d
ln -s ~/git/dotfiles/sway/sway.d/20-autostart.conf ~/.config/sway/sway.d
ln -s ~/git/dotfiles/sway/sway.d/30-visuals.conf ~/.config/sway/sway.d
ln -s ~/git/dotfiles/sway/sway.d/40-output.conf ~/.config/sway/sway.d
ln -s ~/git/dotfiles/sway/sway.d/50-input.conf ~/.config/sway/sway.d
ln -s ~/git/dotfiles/sway/sway.d/60-workspaces.conf ~/.config/sway/sway.d
ln -s ~/git/dotfiles/sway/sway.d/70-floats.conf ~/.config/sway/sway.d
ln -s ~/git/dotfiles/sway/sway.d/80-keybinds.conf ~/.config/sway/sway.d
ln -s ~/git/dotfiles/sway/sway.d/90-bar.conf ~/.config/sway/sway.d
ln -s ~/git/dotfiles/swaylock/config ~/.config/swaylock/config
ln -s ~/git/dotfiles/waybar/config ~/.config/waybar/config
ln -s ~/git/dotfiles/waybar/style.css ~/.config/waybar/style.css
ln -s ~/git/dotfiles/wofi/style.css ~/.config/wofi/style.css
```

## Credits
Many thanks to a bunch of people from whom I have gotten inspiration or taken code snippets from.  
This includes: [mmphego](https://github.com/mmphego/dot-files), [Madic-](https://github.com/Madic-/Sway-DE), [nboughton](https://github.com/nboughton/dotfiles), and more.
