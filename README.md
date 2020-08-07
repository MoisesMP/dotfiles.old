# dotfiles
My Linux settings

bspwm configuration

![Desktop BSPWM](https://raw.githubusercontent.com/MoisesMP/dotfiles/master/Desktop.png)


Distro: Arch Linux

WM: BSPWM

Used

1. Transparency manager = Compton
2. Resolution manager = Xrandr
3. Wallpaper manager = nitrogen
4. Bar = polybar
5. Menu = rofi
6. File explorer = nemo
7. Web navigator = firefox & chromium
8. Terminal = tilix
9. Settings control = gnome-control-center & lxappearance
10. Bluetooth manager = blueberry


# Installation

###### 1. Change to home dir
> cd

###### 2. Clone this repo
> git clone https://github.com/MoisesMP/dotfiles.git

###### 3. Go to dotfiles dir
> cd dotfiles/

###### 5. Copy fonts to local fonts dir (i'll put the fonts in all dirs)
> cp -r fonts/* ~/.local/share/fonts

###### or

> sudo cp -r fonts/* ~/.local/share/fonts

###### 6. Reload font cache
> fc-cache -v

###### 7. Copy everything from .config  to .config dir (backup your config first if you have)
> cd .config
> cp -r * ~/.config/

###### or 

> sudo cp -r * ~/.config/

###### 8. Change to home dir
> cd

###### 9. Go to bspwm dir
> cd ~/.config/bspwm/

###### 10. Give execute permissions to the bspwmrc file
> chmod +x bspwmrc

###### or
> sudo chmod +x bspwmrc
