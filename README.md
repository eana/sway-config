# Dotfiles for sway wm configuration

### Screenshots of my sway configuration

![Screenshot 7](./screenshots/screenshot-7.png "Screenshot 7")

![Screenshot 8](./screenshots/screenshot-8.png "Screenshot 8")

### Used packages:

- [fuzzel](https://archlinux.org/packages/community/x86_64/fuzzel/) - menu launcher
- [swaylock](https://archlinux.org/packages/community/x86_64/swaylock/) - lockscreen
- [grim](https://archlinux.org/packages/community/x86_64/grim/) - screenshot and colorpick utility
- [slurp](https://archlinux.org/packages/community/x86_64/slurp/) - utility for selecting an area
- [light](https://archlinux.org/packages/community/x86_64/light/) - for brightness control
- [pipewire](https://archlinux.org/packages/extra/x86_64/pipewire/)/[pavucontrol](https://archlinux.org/packages/extra/x86_64/pavucontrol/) - for audio control
- [waybar](https://archlinux.org/packages/community/x86_64/waybar/) - bar for swaywm
- [network-manager-applet](https://archlinux.org/packages/extra/x86_64/network-manager-applet/) - wifi applet
- [mako](https://archlinux.org/packages/community/x86_64/mako/) - notification manager
- [earlyoom](https://archlinux.org/packages/community/x86_64/earlyoom/) - out of memory manager
- [redshift-wayland](https://aur.archlinux.org/packages/redshift-wayland-git) - blue light filter
- [blueman](https://archlinux.org/packages/community/x86_64/blueman/) - bluetooth applet
- [parcellite](https://archlinux.org/packages/community/x86_64/parcellite/) - clipboard manager
- [gthumb](https://archlinux.org/packages/extra/x86_64/gthumb/) - image viewer
- [nautilus](https://archlinux.org/packages/extra/x86_64/nautilus/) - file manager
- [mpg123](https://archlinux.org/packages/extra/x86_64/mpg123/) - play sound from terminal
- [otf-font-awesome](https://archlinux.org/packages/community/any/otf-font-awesome/)/[ttf-font-awesome](https://archlinux.org/packages/community/any/ttf-font-awesome/)/[powerline-fonts](https://aur.archlinux.org/packages/powerline-fonts-git) - awesome font
- [polkit](https://archlinux.org/packages/extra/x86_64/polkit/)/[polkit-gnome](https://archlinux.org/packages/community/x86_64/polkit-gnome/)

### Some features

#### Scratchpad indicator:

Shows how much windows is hidden in scratchpad

- Left mouse click - move to scratchpad
- Right mouse click - show windows from scratchpad

#### Battery:

##### Beeper

Plays sound when capacity <= 10% every 60 seconds

##### Indicator

- green - charging
- default - discharging and capacity > 20%
- yellow - discharging and 10% < capacity < 20%
- red, blinking - discharging and capacity < 10%

#### Cpu indicator

- default - normal load
- yellow - load > 70%
- red - load > 90%

### Shortcuts ($mod = Super/Windows logo key on keyboard)

- $mod+Shift+r - reload
- $mod+Return - start terminal
- $mod+q - kill
- $mod+d - start run menu
- $mod+w - start browser
- $mod+e - start file manager
- $mod+0 - lock screen
- $mod+p - pick color
- Print - Take a screenshot of whole screen and copy it to clipboard
- $mod+Print - Take a screenshot of selected region and copy it to clipboard
- $mod+Shift+Print - Take a screenshot of focused window and copy it to clipboard
- Ctrl+Print - Take a screenshot of whole screen and copy to $HOME/Pictures/screenshots (You should create this folder)
- $mod+Ctrl+Print - Take a screenshot of selected region and copy to $HOME/Pictures/screenshots
- $mod+Ctrl+Shift+Print - Take a screenshot of focused window and copy to $HOME/Pictures/screenshots
- $mod+$left - focus left
- $mod+$down - focus down
- $mod+$up - focus up
- $mod+$right - focus right
