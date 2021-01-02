# **These are just random settings I have to set every time I login**
## Havent Figured out how to create a script yet to run them

### Enabling 3 monitors
xrandr --output HDMI-1 --right-of HDMI-0
xrandr --output DP-2 --right-of HDMI-0

### Setting system sound to audio interface
## list sound devices: cat /dev/sndstat
## setting it: sysctl hw.snd.default_unit=n
