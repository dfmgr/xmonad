## xmonad  
  
xmonad is a dynamically tiling X11 window manager  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/xmonad/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install xmonad policykit-1-gnome xfce4-clipman-plugin xfce4-power-manager xfce4-notifyd volumeicon volumeicon-alsa scrot htop
```  

Fedora Based:

```shell
yum install xmonad polkit-gnome xfce4-clipman-plugin xfce4-power-manager xfce4-notifyd volumeicon scrot htop
```  

Arch Based:

```shell
pacman -S xmonad xmonad-contrib polkit-gnome xfce4-clipman-plugin xfce4-notifyd volumeicon scrot htop
```  

MacOS:  

```shell
brew install
```
  
```shell
mv -fv "$HOME/.config/xmonad" "$HOME/.config/xmonad.bak"
git clone https://github.com/dfmgr/xmonad "$HOME/.config/xmonad"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/xmonad" target="_blank" rel="noopener noreferrer">xmonad wiki</a>  |  
  <a href="https://xmonad.org" target="_blank" rel="noopener noreferrer">xmonad site</a>
</p>  
