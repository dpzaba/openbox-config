Openbox configuration
=====================

This is my Openbox configuration, I am using:

- Openbox
- Tint2
- Volumeicon
- PCManFM
- Multimedia keybindings (for Multimedia keyboards)
- Debian/Ubuntu applications menu
- Cool and special keybinding to resize windows (Full size window, Centered window, set window on left or right side)


## Special and Multimedia keybinding

This depends on: alsamixer, rhythmbox, gnome-screenshot, gnome-screensaver-command

## Support

This config is tested in Debian and Ubuntu.

# How to install

To install this configuration, run these commands:

```
sudo apt-get install openbox openbox-session tint2 volumeicon-alsa arandr xrandr obmenu obconf
cd ~ && git clone https://github.com/dpzaba/openbox-config.git
cd openbox-config
sh install.sh
```

Warning: this will overwrite your previous configuration.
