# dwm-immortale
Simple dwm script for X uses on Gentoo Linux.

Instructions:
- unpack dwm-immortale.tar, edit config.h and config.def.h
- change fonts, and whatever you want to use dwm.
- run $doas make clean install

I don't remember if you'll need to install:

Nerd Fonts or Awesome Fonts, but I think so.

Don't forget install rofi or dmenu, terminal like - st,kitty or alacritty.

edit /home/user/.xinitrc via vi,vim or your favourite text editor.

mv dwmicon to /usr/bin/

put to file .xinitrc text: 

exec /usr/bin/dwmicon &

exec dwm 

then save file and run:

$startx

Enjoy.

If you want patches go to official suckless git repo to get patches.
