Found this article to switch alt and control position on keyboard.

[http://xahlee.info/linux/linux_swap_control_and_alt_xmodmap.html](http://xahlee.info/linux/linux_swap_control_and_alt_xmodmap.html)

```bash
clear control
clear mod1
keycode 37 = Alt_L Meta_L
keycode 105 = Alt_R Meta_R
keycode 64 = Control_L
keycode 108 = Control_R
add control = Control_L Control_R
add mod1 = Alt_L Meta_L
```

Also needed to add this file to `~/.config/autostart` to allow the file to be loaded on start up. This was on debian.

```bash
[Desktop Entry]
Name=MyXmodmap
Exec=/usr/bin/xmodmap /home/rrc/.Xmodmap
Terminal=false
Type=Application
```
