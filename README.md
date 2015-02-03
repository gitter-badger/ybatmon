ybatmon
=======

[![Join the chat at https://gitter.im/yosh-se/ybatmon](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/yosh-se/ybatmon?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Small notification area battery monitor written in python and gtk. Nothing fancy, nothing clever.
t reads battery info straight from /sys/class/power_supply/BAT0/.

I start it with a small bash script like so:

```
#!/bin/sh
nohup python -u /path/to/ybatmon.py  &
```

Dependencies
======
python modules os, sys, gtk, glib

