# RetroFW Changelog

The next list is all the changes registered on the **custom firmware** version updates.

## 2.1 _(Feb 14, 2020)_

Kernel:
- Fine tuned low battery indicator level to 3500 mv (3400 mv for IPS panels)
- Fixed issue with IPU and V-Sync that was causing tearing in the first lines drawn in some screens
- Using Select+Power to kill the current app no longer unmounts the external SD Card

Root FS:
- Fixed SD Card mounting flags. VFAT partitions are using ```shortname=lower``` flag and will force MS-DOS compatible filenames to lowercase
- Updated Recovery Mode GUI and keybindings, fixing an issue where sometimes it would close the app right after entering it
- Added ```/etc/os-release``` to identify the RetroFW version
- ~~Added ```libopk``` and ```opkrun```~~ (OPKs are mounted in ```/mnt``` by default)
- Added ```scandir``` Python module to distribution

Userspace (GMenuNX):
- Improved skin assets scaling and loading logic
- Added back the power timeout option
- Faster file browsing
- Fixed OPK parameters parsing that were preventing to save Selector Browser options
- Links has CPU clock set to 600 MHz by default
- Fixed an issue with suspend timer on boot
- Output Log is shown when re-entering GMenuNX
- Improved input handling
- Link Selector options are now OFF / AUTO / Manual, not being linked to Remember Selection anymore.
- Merged "Install Package" and "Add Link" options. If you browse to an IPK or OPK it will perform the install instead of adding a link.
- Fixed issues with input being registered twice in some devices
- L&R buttons now behave consistently in the brightness adjust menu

## 2.0 _(Dec 20, 2019)_
- Added support for Retro Arcade Mini (RS-07)
- Added support for IPS displays
- OPK (squashfs) packages are now supported alongside IPK
- OPK files can be stored on an external SD card
- Auto-scan for OPK files on the external SD card
- exFAT filesystem is now supported on external SD cards
- OPKs and IPKs can be uninstalled from the main menu
- TV out (limits CPU to 528MHz when in use)
- Scale mode allows you to stretch your games to Aspect, Original, or Stretch
- Scale mode on the Retro Mini Arcade (RS-07) additionally supports 4:3 mode
- Low battery notification
- Significant improvements in memory utilization and performance
- Recovery mode with device tools including remote access; developer mode
- Force kill current application (SELECT+POWER)
- Updated default theme based on Fontes theme
- In-game device suspend by holding Power for 3 seconds
- Press select in the file chooser to access a shortcuts menu
- New Favorites section provides fast links to your favorite games (use select menu in file chooser)

**Boot Combos**
- Hold (Power or Select) + (A or B): Recovery mode
- Hold (Power or Select) + Y: Developer mode <- previously was L
- Hold R on boot: Boot external SD card

**System combos**
- Select + Power: Kill init pid
- Hold power 1s: Enter suspend mode
- Hold power >4s: Power off the device

## 1.2.1 _(Nov 08, 2019)_
- Updated installation scripts to better represent devices currently on the market

## 1.2 _(Mar 02, 2019)_
- Fix boot lag due to bad behaved FAT32 partition in some uSD Cards

## 1.1 _(Feb 24, 2019)_
- Rebuilt rootfs based on buildroot-2018.02.11
- Add OGG support
- exFAT support (experimental)
- Add Python + PyGame libraries
- Improved recovery mode
  - Improved automatic SD card resizing
  - Added file system check mode
- Fix power off bug in Kernel
