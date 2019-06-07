# VNCGit

vncserver [:display] [-geometry widthxheight] [-depth depth] [-pixelformat rgbNNN|bgrNNN] [-name desktop-name] [Xvnc-options...]

```
vncserver -geometry 800x600 -depth 16 :1
vncserver -kill :1
vncserver -help
vncserver -list
```
Set up VNC to connect to desktop session (RasPi, AWS, etc)

vncserver  : https://www.tightvnc.com/vncserver.1.php

vncpasswd  : https://www.tightvnc.com/vncpasswd.1.php

vncviwer   : https://www.tightvnc.com/vncviewer.1.php

# FILES

/etc/tightvncserver.conf        : System-wide configuration file of TightVNC Server. 

$HOME/.vnc/tightvncserver.conf  : User configuration file of TightVNC Server. (override system-wide configuration). 


# Some interesting links:

VNC viewer donload page

> https://www.realvnc.com/en/connect/download/viewer/

# Instruction for RPI

> https://www.realvnc.com/en/connect/docs/raspberry-pi.html#raspberry-pi-minecraft-troubleshoot

> https://www.raspberrypi.org/documentation/remote-access/vnc/
