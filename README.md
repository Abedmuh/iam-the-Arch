### Linux for Normies

youre about to change your OS to linux and i u have no idea what to do here a journey of using linux like normies

## Instalation
here u have linux image ready to install on your laptop. u will be guided to root linux arch

# Connect to internet
```
iwctl
device list
station <wlan> scan
station <wlan> get-networks
station <wlan> connect "<SSID-wifi>"
exit
```
# install linux
``` archinstall```

then follow all guide this should be easy as fk

## Your daily lives
if u are new user to linux u probably suprise hw difficult to use and somehow u have no idea what u should do. in linux arch u need to set everything from network, backgrod even in some case your double click the mouse pad doesnt work. here was some daily life of thing that minght u need to install 

# 1. Package Manager
a package manager, rn u probably using sudo pacman(package manager) install <app>. but yay or paru provide easy way to install and list all version of the stuff u need to install. with yay u can just type 
```
yay -S <app>
```
flag S stand for syncronize  
if your app isnt registered on yay aur u can download it then type 
```
sudo pacman -U <app>
```
flag `U` stand for Upgrade if there new one use this too  
and for uninstall stuff use flag `Rns`

# 2. Daily Active Tools
context of daily mean open some stuff that u need actively on linux not running in background i recommend u to use 
- VlC, Video player
- VScode | Vim , open text based
- Office
- spectacle, for screenshoot

# 3. Daily Passive Tools 
- networkmanager, connect active instal using iwctl
- zsh, a bash shell for rcing linux. u probably want use oh-my-zsh or power-level-10k
- dmenu, a menu for serach app
- feh, set background
- usbutils, list all usb
- alsa-utils,  Advanced Linux Sound Architecture :  
- pulse audio, GUI soundsystem

# 4. Developer
- docker
- postman
- vmware-workstation
- postgres

