# RetroFW Changelog

The next list is all the changes registered on the **custom firmware** version updates.

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
