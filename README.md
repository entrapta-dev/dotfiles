# dotfiles
dotfiles and configs for heron laptop  
this readme is a work in progress  
so are the dotfiles  
honestly, I have no idea what I'm doing  
this is my first time messing around with a window manager  
not to mention arch (btw)  

## what it currently looks like
![preview](./preview.png)

## The Setup
- **OS:** [Arch Linux](https://archlinux.org/)
- **Compositor:** [sway](https://github.com/swaywm/sway)  
- **Bar:** [waybar](https://github.com/Alexays/Waybar)
- ...

## Additional Requirements
- [wob](https://github.com/francma/wob)  
- [grim](https://github.com/emersion/grim) - screenshot
- [grimshot](https://aur.archlinux.org/packages/grimshot/) (AUR) - screenshot
- feh - image viewer
- [mako](https://github.com/emersion/mako) - notifications
- --blueman-- bluetooth manager
- ...

## symlinks
```
sudo ln -s ~/Sync/git/dotfiles/sway/config ~/.config/sway/config
sudo ln -s ~/Sync/git/dotfiles/waybar/config ~/.config/waybar/config
sudo ln -s ~/Sync/git/dotfiles/waybar/style.css ~/.config/waybar/style.css
sudo ln -s ~/Sync/git/dotfiles/alacritty/alacritty.yml ~/.config/alacritty/alacritty.yml
sudo ln -s ~/Sync/git/dotfiles/alacritty/dracula.yml ~/.config/alacritty/dracula.yml
```
