# Dotfiles
My Linux settings

#### BSPWM Configuration

![Desktop BSPWM](https://raw.githubusercontent.com/MoisesMP/dotfiles/master/DesktopB2.png)
![Desktop BSPWM](https://raw.githubusercontent.com/MoisesMP/dotfiles/master/nemo.png)

#### Push Notifications
![Notifications](https://raw.githubusercontent.com/MoisesMP/dotfiles/master/Nottify.png)

Distro: Arch Linux

WM: BSPWM

Shell: zsh : oh my zsh (alanpeabody)

Gtk Theme = <a href="https://www.gnome-look.org/p/1357889/"><Orchis>



Icon Theme = <a href="https://www.gnome-look.org/p/1270110/"><Marwaita Icons>



Cursor Theme = <a href="https://www.gnome-look.org/p/1358330/"><Vimix Cursors Theme>


# Used

1. Transparency manager = Compton
2. Resolution manager = Xrandr
3. Wallpaper manager = nitrogen or feh
4. Bar = polybar
5. Menu = rofi
6. File explorer = nemo & thunar
7. Web navigator =  chromium & firefox
8. Terminal = tilix & gmome-terminal
9. Settings control = gnome-control-center & lxappearance
10. Bluetooth manager = blueberry
11. Menu Network = networkManager_dmenu
12. Push Notifications = dunst
13. Lolcat = lolcat

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

###### 8. Go to dotfiles dir
> cd ..

###### 9. Copy .zshrc to user dir
> cp -r .zshrc ~/

###### or
> sudo cp -r .zshrc ~/ 

###### 10. Change to home dir
> cd

###### 11. Give execute permissions to the .zshrc file
> chmod +x .zshrc

###### or
> sudo chmod +x .zshrc

###### 12. Go to bspwm dir
> cd ~/.config/bspwm/


###### 13. Give execute permissions to the bspwmrc file
> chmod +x bspwmrc

###### or
> sudo chmod +x bspwmrc

# Desktop Beta 1

![Desktop BSPWM](https://raw.githubusercontent.com/MoisesMP/dotfiles/master/Desktop.png)

# Changelogs

1. Added Module Storage 
2. Added Module Title
3. Added Module Update
4. Added Menu NetworkManager_dmenu
5. Added Nottify Panel = dunst
6. Added Lolcat in Neofetch
7. Added Cava Theme
8. Added Htop Theme
9. Added Neofetch + Lolcat

# Notes

#### If you have an error with the wifi module, please change the network interface in

> ~/config/polybar/control.ini

###### To know the name of the network interface, type in the terminal

> ip addr

###### note the name of the wifi network interface starts with wl

