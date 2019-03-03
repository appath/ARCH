#### Installing i3-grap

Install from the official repository, i3-grap directly window manager.

Then we clone the theme files.
git clone https://github.com/appath/dotfiles.git

PKG pacman -S
```bash
- xorg 
- xorg-xinit 
- i3-gaps 
- i3blocks 
- rxvt-unicode 
- tree 
- git 
- tmux 
- vim 
- mc 
- fontconfig
```

install font

git clone https://github.com/whitelynx/artwiz-fonts-wl

```bash
# cd ./MAKEFILES/artwiz-fonts-wl
```

Building Fonts
```bash
# make
```
Installing Fonts
```bash
# make install
```
On Arch Linux, this file is named /etc/fonts/conf.d/70-no-bitmaps.conf, and the file /etc/fonts/conf.avail/70-yes-bitmaps.conf should be linked in its place:
```bash
# rm /etc/fonts/conf.d/70-no-bitmaps.conf
# ln -s /etc/fonts/conf.avail/70-yes-bitmaps.conf /etc/fonts/conf.d/
```

#### KeyMod
Mod1+
Mod1+Return > Terminal
Mod1+m > Mc (File Manager)
Mod1+t > Tmux
Mod1+g > nSnake (Game)

#### Exhaust
![i3](*.png)