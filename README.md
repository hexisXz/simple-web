# simple-web
a distro that is only the browser and a bar with a menu system, the base is bspwm and waterfox. you cant change desktops and there aren't any keybins except volume up, brightness up, volume down, brightness down and an app launcher.


## depends

``` sh
sudo apt install polybar sxhkd bspwm picom font-awesome rofi flatpak xwallpaper git 
```


``` sh 
git clone --depth=1 https://github.com/adi1090x/rofi.git ; cd rofi ; chmod +x setup.sh
```


## install 

``` sh
git clone https://github.com/hexisXz/simple-web.git && cd simple-web && mv bspwm ~/.config && mv polybar ~/.config && mv sxhkd ~/.config && mv wallpapers ~/.config
```
