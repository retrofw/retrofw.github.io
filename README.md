# Announcements & Updates

### [2020-05-06: RetroFW v2.2 is out!](https://github.com/retrofw/retrofw.github.io/releases/tag/v2.2)

RetroFW v2.2 is out. This time it's mostly bugfixes and some Q.O.L. changes in the system recovery. Now it will create the needed partition layout during the first boot. This is faster and more reliable than partition expander used in previous versions.

Also, libopk and opkrun are finally included! Now you can enjoy other amazing GUIs such as pyMenu and SimpleMenu!

Download the latest revision in the [Releases Page](https://github.com/retrofw/retrofw.github.io/releases).



<details><summary>Old releases</summary>


### [2020-02-14: RetroFW v2.1 is out!](https://github.com/retrofw/retrofw.github.io/releases/tag/v2.1)

RetroFW v2.1 is out with a new batch of bug fixes. It brings more stability, improvements and also features for the developers. Just in time to show your valentine how much you love them!

This release brings all the performance, devices, features, ports, and fun that you remember from 2.0! 2.1 adds important fixes like the vfat configuration, improved low-battery notification, and the ability to scan ExFAT formatted cards for OPK releases. It also brings us cool new features like the fastest file browsing ever, ~~libopk and opkrun tools~~, default CPU speed of 600MHz, faster debugging loops with better log file management, and too many small tweaks to mention!

(Fix to come soon for libopk and opkrun!)

Check the changelog and download the latest revision in the [Releases Page](https://github.com/retrofw/retrofw.github.io/releases).

### [2019-12-27: RetroFW 2.0 patch 001 (vfat-lower)](https://github.com/retrofw/retrofw.github.io/releases/download/2.0/patch-2.0-001-vfat-lower.ipk)
This little patch rollbacks a change we made to VFAT mounting options (from "lower" to "mixed"). We're rolling it back because, in combination with a Windows copy bug, it caused FBA and NeoGeo ROMS not to be recognized by emulators when put in internal SD. Just install it from Explorer like a normal IPK.

[patch-2.0-001-vfat-lower.ipk](https://github.com/retrofw/retrofw.github.io/releases/download/2.0/patch-2.0-001-vfat-lower.ipk)

### [2019-12-20: RetroFW v2.0 is out!](https://github.com/retrofw/retrofw.github.io/releases/tag/2.0)

After many months of development and testing, it is my great pleasure to officially announce the release of RetroFW 2.0!

This release brings more performance, more devices, more features, more ports, and more fun! With the addition of OPK package support, you can now bring your emulator installations from device to device. Just like your ROMs!

Check the changelog and download the latest revision in the [Releases Page](https://github.com/retrofw/retrofw.github.io/releases).


</details>



# Setup & Info

- Check the [installation guide](https://github.com/retrofw/retrofw.github.io/wiki/Install-Firmware) in our wiki
- Check the version details history in our [changelog](https://retrofw.github.io/CHANGELOG)
- Grab a [Starter Pack](https://github.com/retrofw/retrofw.github.io/releases/tag/StarterPack2.0) to start playing games

# Development

- Learn how to develop and port programs with our [developer tutorial](https://github.com/retrofw/retrofw.github.io/wiki/Configuring-a-Toolchain)
- Collaborate with others by looking up and [claiming software to port](https://docs.google.com/spreadsheets/d/1CfDmrbuRfihLl-emOtaS3RMg6t_em3EQQkQupw7vCRw/edit?usp=sharing)
- Check out the [Buildroot](https://github.com/retrofw/buildroot) repository to build your own toolchain
- Check out the [Kernel](https://github.com/retrofw/kernel) and [U-Boot](https://github.com/retrofw/uboot) repositories to customize the system


# Resources

- Check the [emulators and apps](https://github.com/retrofw/retrofw.github.io/wiki/Emulators-and-Apps) list in our wiki
- Report issues in our [bug tracker](https://github.com/retrofw/retrofw.github.io/issues)
- Join our [**Discord** chat server](https://discord.gg/CX67MCH) for more support
