# DWM
This is my personal fork of [DWM](https://dwm.suckless.org/), tailored to fit my specific preferences and workflow. While it's available under a free software license and open for auditing, please note that its customization is only intended for my personal use.

# Patches
- [`actualfullscreen`](https://dwm.suckless.org/patches/actualfullscreen/)
  - Toggle fullscreen for a window with a keybind.
- [`attachbottom`](https://dwm.suckless.org/patches/attachbottom/)
  - New clients attach at the bottom of the stack instead of the top.
- [`movestack`](https://dwm.suckless.org/patches/movestack/)
  - Allows you to move clients around in the stack and swap them with the master.
- [`pertag`](https://dwm.suckless.org/patches/pertag/)
  - Enables one layout per tag.
- [`tiledmove`](https://dwm.suckless.org/patches/tiledmove/)
  - Tiled clients when moved will swap with other tiled clients that overlap with the cursor.

This fork contains undocumented modifications as well.

# Setup
Clone the repository:
```
git clone https://github.com/fliplus/dwm
cd dwm
```

Build DWM:
```
sudo make clean install
```

Add the following line to your ~/.xinitrc to start DWM using startx:
```
exec dwm
```