# linux-problem
kasus error ketika pakai linux
# error alt + prtsc linux mint
fixed:
```
$ sudo ln -s  /usr/bin/gnome-screenshot /usr/bin/mate-screenshot
$ sudo apt-get install gnome-screenshot
```

# bypass battery linux
```
$ sudo apt-get remove indicator-power
$ reboot
```

# make pip packet is PYPI

# chmod and chown
```
chmod untuk hak akses 
contoh: chmod 777 index.php

chown untuk akses group dan user
contoh: chown nobody:root index.php
```
# open folder on terminal command
```
nautilus folder1
```

# fix kazam video play in android
```
$ sudo apt-get install ffmpeg
$ ffmpeg -y -i input.mp4 -c:v libx264 -c:a aac -strict experimental -tune fastdecode -pix_fmt yuv420p -b:a 192k -ar 48000 output_file.mp4
```

# bongkar source code apk
```
bongkar source android

========
apktool d name.apk

;;;;
atau
;;;;

ubah name.apak -> name.zip ->extract
========

=======
dex2jar classes.dex

;;;;
atau
;;;;

d2j-dex2jar.sh classes.dex
=======

```
