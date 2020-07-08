# macbook-cz-keyboard-layout-linux
This repository is made to save czech keyboard layout for Macbook for linux distributions.


Installation:
1. Copy the files into your `/usr/share/X11/xkb` directory:
   ```
   $ cp xkb/rules/evdev.xml /usr/share/X11/xkb/rules/evdev.xml
   $ cp xkb/symbols/cz /usr/share/X11/xkb/symbols/cz
   
2. Reconfigure the xkb-data:
   ```
   $ sudo dpkg-reconfigure xkb-data   
3. Done! You can see in your keyboards layouts "Czech (QWERTZ, Macintosh)"