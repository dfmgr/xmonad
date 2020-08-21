## xmonad  
  
xmonad is a dynamically tiling X11 window manager  
  
requires:

```shell
apt install xmonad policykit-1-gnome xfce4-clipman-plugin xfce4-power-manager xfce4-notifyd volumeicon volumeicon-alsa scrot htop
```  

```shell
yum install xmonad polkit-gnome xfce4-clipman-plugin xfce4-power-manager xfce4-notifyd volumeicon scrot htop
```  

```shell
pacman -S xmonad xmonad-contrib polkit-gnome xfce4-clipman-plugin xfce4-notifyd volumeicon scrot htop
```  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/xmonad/raw/master/install.sh)"
```

Manual install:

```shell
mv -fv "$HOME/.config/xmonad" "$HOME/.config/xmonad.bak"
git clone https://github.com/dfmgr/xmonad "$HOME/.config/xmonad"
ln -sf "$HOME/.config/xmonad" "$HOME/.xmonad"
```
  
  
# My Keybindings

The MODKEY is set to the Super key (aka the Windows key).

| Keybinding             | Action                                                           |
| :--------------------- | :--------------------------------------------------------------- |
| `MODKEY + SHIFT + c`   | closes window with focus                                         |
| `MODKEY + SHIFT + ESC` | quits xmonad                                                     |
| `MODKEY + j`           | windows focus down (switches focus between windows in the stack) |
| `MODKEY + k`           | windows focus up (switches focus between windows in the stack)   |
| `MODKEY + SHIFT + j`   | windows swap down (swap windows in the stack)                    |
| `MODKEY + SHIFT + k`   | windows swap up (swap the windows in the stack)                  |
| `MODKEY + h`           | shrink window (decreases window width)                           |
| `MODKEY + l`           | expand window (increases window width)                           |
| `MODKEY + w`           | switches focus to monitor 1                                      |
| `MODKEY + e`           | switches focus to monitor 2                                      |
| `MODKEY + r`           | switches focus to monitor 3                                      |
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/Xmonad" target="_blank">xmonad support</a>  |  
  <a href="https://xmonad.org/" target="_blank">xmonad site</a>
</p>  
