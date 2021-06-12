# dotfiles
dotfiles and configs for heron laptop  
this readme is a work in progress  
so are the dotfiles  
honestly, I have no idea what I'm doing  
this is my first time messing around with a window manager  
not to mention arch (btw)  

## what it currently looks like
![preview](./preview.png)

## The Packages
- [alacritty](https://github.com/alacritty/alacritty) - Terminal emulator
- brightnessctl - Monitor brightness control
- [font-awesome](https://archlinux.org/packages/community/any/font-awesome/) - Fancy icons
- [grim](https://github.com/emersion/grim) - Image grabber
- [grimshot](https://aur.archlinux.org/packages/grimshot/) (AUR) - Better screenshot handling
- feh - image viewer
- [mako](https://github.com/emersion/mako) - notifications
- nerd-fonts-complete ([AUR](https://aur.archlinux.org/packages/nerd-fonts-complete/)) - more fonts
- pavucontrol - PulseAudio Volume Control
- playerctl - enable media controls keys
- [sway](https://github.com/swaywm/sway)
- [swaylock-effects](https://github.com/mortie/swaylock-effects) - Better lockscreen
- [wal](https://github.com/dylanaraps/wal) (AUR) - Colorscheme templates
- [waybar](https://github.com/Alexays/Waybar)
- [wob](https://github.com/francma/wob) - on screen display
- [wofi](https://hg.sr.ht/~scoopta/wofi) - dmenu replacement
- ...

## symlinks
```
sudo ln -s ~/git/dotfiles/sway/config ~/.config/sway/config
sudo ln -s ~/git/dotfiles/waybar/config ~/.config/waybar/config
sudo ln -s ~/git/dotfiles/waybar/style.css ~/.config/waybar/style.css
sudo ln -s ~/git/dotfiles/alacritty/alacritty.yml ~/.config/alacritty/alacritty.yml
sudo ln -s ~/git/dotfiles/alacritty/dracula.yml ~/.config/alacritty/dracula.yml
sudo ln -s ~/git/dotfiles/swaylock/config ~/.config/swaylock/config
```

## Credits
Many thanks to a bunch of people from whom I have gotten inspiration or taken code snippets from.  
This includes: [mmphego](https://github.com/mmphego/dot-files), [Madic-](https://github.com/Madic-/Sway-DE), [nboughton](https://github.com/nboughton/dotfiles), and more.
