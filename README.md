# dotfiles
dotfiles and configs for heron laptop  
running ArchLinux (btw) with sway WM, no DE  
Using [Dracula Theme](https://draculatheme.com/) wherever possible for a consistent look.

## what it currently looks like
![preview](./preview.png)

## Official Packages
- [brightnessctl](https://archlinux.org/packages/community/x86_64/brightnessctl/) - Monitor brightness control
- [btop](https://archlinux.org/packages/community/x86_64/btop/) - A monitor of system resources, bpytop ported to C++
- [font-awesome](https://archlinux.org/packages/community/any/font-awesome/) - Fancy icons - [(Icon Picker)](https://fontawesome.com/v5.15/icons?d=gallery&p=2&m=free)
- [foot](https://archlinux.org/packages/community/x86_64/foot/) - Fast, lightweight, and minimalistic Wayland terminal emulator
- [grim](https://archlinux.org/packages/community/x86_64/grim/) *[(GitHub)](https://github.com/emersion/grim)* - Screenshot utility for Wayland
- [feh](https://archlinux.org/packages/extra/x86_64/feh/) - Fast and light imlib2-based image viewer
- [mako](https://archlinux.org/packages/community/x86_64/mako/) *[(GitHub)](https://github.com/emersion/mako)* - Wayland notification daemon
- [pavucontrol](https://archlinux.org/packages/extra/x86_64/pavucontrol/) - PulseAudio Volume Control GUI
- [playerctl](https://archlinux.org/packages/community/x86_64/playerctl/) - enable media controls keys
- [sway](https://archlinux.org/packages/community/x86_64/sway/) *[(GitHub)](https://github.com/swaywm/sway)* - Tiling Wayland compositor and replacement for the i3 window manager
- [swaylock](https://archlinux.org/packages/community/x86_64/swaylock/) *[(GitHub)](https://github.com/swaywm/swaylock)* - Screen locker for Wayland
- [waybar](https://archlinux.org/packages/community/x86_64/waybar/) *[(GitHub)](https://github.com/Alexays/Waybar)* - Highly customizable Wayland bar for Sway and Wlroots based compositors
- [wofi](https://archlinux.org/packages/community/x86_64/wofi/) *[(SourceHut)](https://hg.sr.ht/~scoopta/wofi)* - launcher for wlroots-based wayland compositors
- [zsh](https://archlinux.org/packages/extra/x86_64/zsh/) - A very advanced and programmable command interpreter (shell) for UNIX

## External Packages
- [cava](https://aur.archlinux.org/packages/cava/) *[(GitHub)](https://github.com/karlstav/cava)* - CLI audio visualizer
- [grimshot](https://aur.archlinux.org/packages/grimshot/) - A helper for screenshots within sway.
- [ncspot](https://aur.archlinux.org/packages/ncspot/) *[(GitHub)](https://github.com/hrkfdn/ncspot)* - Spotify CLI client
- [oh-my-zsh] *[GitHub](https://github.com/ohmyzsh/ohmyzsh)* - zsh configuration manager
- [powerlevel10k] *[GitHub](https://github.com/romkatv/powerlevel10k)* - zsh theme

## symlinks used
*(This needs a proper cleanup and an automated script at some point.)*
```
ln -s ~/git/dotfiles/cava/config ~/.config/cava/config
ln -s ~/git/dotfiles/foot/foot.ini ~/.config/foot/foot.ini
ln -s ~/git/dotfiles/gtk-3.0/settings.ini ~/.config/gtk-3.0/settings.ini
ln -s ~/git/dotfiles/mako/config ~/.config/mako/config
ln -s ~/git/dotfiles/ncspot/config.toml ~/.config/ncspot/config.toml
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
ln -s ~/git/dotfiles/zsh/.zshrc ~/.zshrc
```

## Credits
Many thanks to a bunch of people from whom I have gotten inspiration or taken code snippets from.  
This includes: [mmphego](https://github.com/mmphego/dot-files), [Madic-](https://github.com/Madic-/Sway-DE), [nboughton](https://github.com/nboughton/dotfiles), and more.
