# patched-dwm
This repo created to hold and share the patched version of [dwm](https://dwm.suckless.org). List of applied patches are here. Because customization choices vary from person to person, there is **no customization** applied.

## Applied patches

### Patches from suckless.org
```
dwm-6.2-urg-border.diff
dwm-actualfullscreen-20191112-cb3f58a.diff
dwm-attachaside-20180126-db22360.diff
dwm-cfacts-20200913-61bb8b2.diff
dwm-cfacts_bottomstack-6.2.diff
dwm-cyclelayouts-20180524-6.2.diff
dwm-decorhints-6.2.diff
dwm-float-border-color-6.2.diff
dwm-focusmaster-20200717-bb2e722.diff
dwm-goback-20201227-61bb8b2.diff
dwm-inplacerotate-6.2.diff
dwm-keypressrelease-6.0.diff
dwm-killunsel-ceac8c91ff.diff
dwm-noborderfloatingfix-6.2.diff
dwm-pertag-20200914-61bb8b2.diff
dwm-savefloats-20181212-b69c870.diff
dwm-scratchpad-6.2.diff
dwm-systray-20200914-61bb8b2.diff
dwm-zoomswap-6.2.diff
```
And `dwm-keypressrelease-6.0.diff` was applied by hand and made compatible with other patches.
And `dwm-killunsel-ceac8c91ff.diff` was made compatible with systray patch.

### Patches from me
```
dwm-not-draw-vacant-tags-6.2.diff
dwm-not-focus-to-client-with-mouse-6.2.diff
```
The code included by draw vacant tags patch taken from [LukeSmithxyz/dwm](https://github.com/LukeSmithxyz/dwm).

## Installation
Just clone this repo and compile with `make install` (`sudo` may be needed).
