<h1>Simple dwm script for X uses on Gentoo Linux.</h1>
<p>First read the source code RTSC ;) any question bofh@retro-technology.pl</p>
<p><img alt="" src="dwm.png" /></p>
<p><a href="https://dwm.suckless.org/">DWM</a> is a dynamic window manager for X. It manages windows in tiled, monocle and floating layouts. All of the layouts can be applied dynamically, optimising the environment for the application in use and the task performed.</p>
<h2>Installation unofficial:</h2>
<p>Unpack dwm-immortale.tar, edit config.h and config.def.h
- change fonts, and whatever you want to use dwm.
- download the file dwmicon separately from the dwm-immortale directory, because I did not put it in the package.
- edit dwmicon for sure this script work on Gentoo Linux, then run:</p>
<p><code>doas mv dwmicon /usr/bin/</code></p>
<p>Run compile dwm:</p>
<p><code>doas make clean install</code></p>
<h2>I don't remember if you'll need to install, Nerd Fonts or Awesome Fonts, but I think so.
Don't forget install rofi or dmenu, terminal like - st,kitty or alacritty.</h2>
<p>Edit <code>.xinitrc</code> configuration file:</p>
<p><code>vim ~/.xinitrc</code></p>
<p>Inside <code>.xinitrc</code> type:</p>
<p><code>/usr/bin/dwmicon &</code></p>
<p><code>exec dwm</code></p>
<p>then save file and run command:</p>
<p><code>startx</code></p>
<h2>Enjoy.If you want patches go to official suckless git repo to get patches.</h2<p>
<img src="1.png" alt="scrot of dwm" width="500" height="600"> </p>


