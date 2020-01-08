# Announcements & Updates

### [2019-12-27: RetroFW 2.0 patch 001 (vfat-lower)](https://github.com/retrofw/firmware/releases/download/2.0/patch-2.0-001-vfat-lower.ipk)
This little patch rollbacks a change we made to VFAT mounting options (from "lower" to "mixed"). We're rolling it back because, in combination with a Windows copy bug, it caused FBA and NeoGeo ROMS not to be recognized by emulators when put in internal SD. Just install it from Explorer like a normal IPK.

[patch-2.0-001-vfat-lower.ipk](https://github.com/retrofw/firmware/releases/download/2.0/patch-2.0-001-vfat-lower.ipk)

### [2019-12-20: RetroFW v2.0 is out!](https://github.com/retrofw/firmware/releases/latest)

After many months of development and testing, it is my great pleasure to officially announce the release of RetroFW 2.0! 

This release brings more performance, more devices, more features, more ports, and more fun! With the addition of OPK package support, you can now bring your emulator installations from device to device. Just like your ROMs!

Check the changelog and download the latest revision in the [Releases Page](https://github.com/retrofw/firmware/releases/latest).

# Setup & Info

- Check the [installation guide](https://github.com/retrofw/firmware/wiki/Install-Firmware) in our wiki
- Check the version details history in our [changelog](https://github.com/retrofw/firmware/blob/master/CHANGELOG.md)
- Grab a [Starter Pack](https://github.com/retrofw/firmware/releases/tag/StarterPack2.0) to start playing games 
- Join our [**Discord** chat server](https://discord.gg/CX67MCH) for more support

# Development

- Learn how to develop and port programs with our [developer tutorial](https://docs.google.com/document/d/19kJXO3EZ8XCoeporuUUgV_S93AaPbSagza3sAgBILu8/edit?usp=sharing)
- Collaborate with others by looking up and [claiming software to port](https://docs.google.com/spreadsheets/d/1CfDmrbuRfihLl-emOtaS3RMg6t_em3EQQkQupw7vCRw/edit?usp=sharing)


# Resources

The following list is a catalog of all **OPK** and **IPK** _(Install Packages)_ available for the _RetroFW_ operating system.

### Apps

Download | Description | Dev / Port by
:------:|:------|:------:
[GMenuNX](https://github.com/pingflood/gmenunx/releases/download/latest/gmenunx.ipk) | SDL frontend and launcher | [@pingflood](https://github.com/pingflood)
[PyMenu](https://github.com/JackD83/PyMenu/releases/latest) | Python frontend and launcher | [@JackD83](https://github.com/JackD83)
[Commander](https://github.com/retrofw/dinguxcommander/releases/download/latest/commander.ipk) | File manager | [@jbanes](https://github.com/jbanes) 
[Glutexto](https://github.com/retrofw/glutexto/releases/download/latest/glutexto.ipk) | Text editor | [@jbanes](https://github.com/jbanes) 
[gnash](https://github.com/retrofw/gnash/releases/download/latest/gnash.ipk) | Gnash | [@gameblabla](https://github.com/gameblabla) 
[lgpt](https://github.com/retrofw/lgpt/releases/download/latest/lgpt.ipk) | LittleGPTracker | [@gameblabla](https://github.com/gameblabla) 
[o2xiv](https://github.com/scooterpsu/o2xiv/releases/download/latest/o2xiv.ipk) | o2xiv -  Image Viewer | [@scooterpsu](https://github.com/scooterpsu) 

### Tools

Download | Description | Dev / Port by
:------:|:------|:------:
[BattLog](https://github.com/pingflood/battlog/releases/latest/download/battlog.opk) | Log battery discharge profile | [@pingflood](https://github.com/pingflood)
[IO Tester](https://github.com/pingflood/iotester/releases/download/initial/iotester.ipk) | Input/output tester for the RetroGame | [@pingflood](https://github.com/pingflood)
[PixMassage](https://github.com/pingflood/pixmassage/releases/download/initial/pixmassage.ipk) | Try to fix LCD stuck pixel | [@pingflood](https://github.com/pingflood)
[GPmark](https://github.com/pingflood/gpmark/releases/download/latest/gpmark.ipk) | Graphics benchmark | [@pingflood](https://github.com/pingflood)
[Midi Enabler](https://github.com/scooterpsu/midi-enabler/releases/download/latest/midi-enabler.ipk) | Midi Enabler | [@scooterpsu](https://github.com/scooterpsu/midi-enabler)
[Terminal](https://ozgur.kazancci.com/jutleys/10-RG-300/IPK%20Files/apps/st-sdl-terminal.ipk) | Command-line terminal application | |

### Emulators

Download | System | Dev / Port by
:------:|:------|:------:
[colem](https://github.com/pingflood/colem/releases/latest/download/colem.opk) | ColecoVision | [@pingflood](https://github.com/pingflood) 
[dingux-2600](https://github.com/pingflood/dingux-2600/releases/latest/download/dingux-2600.opk) | Atari 2600 | [@pingflood](https://github.com/pingflood) 
[dingux-atari](https://github.com/pingflood/dingux-atari/releases/download/latest/dingux-atari.ipk) | Atari 800 | [@pingflood](https://github.com/pingflood) 
[dingux-cap32](https://github.com/pingflood/dingux-cap32/releases/download/latest/dingux-cap32.ipk) | Amstrad CPC | [@pingflood](https://github.com/pingflood) 
[dingux-msx](https://github.com/pingflood/dingux-msx/releases/download/latest/dingux-msx.ipk) | MSX | [@pingflood](https://github.com/pingflood) 
[dosbox](https://github.com/retrofw/dosbox/releases/download/latest/dosbox.ipk) | DOSBox - MS-DOS Emulator | [@jbanes](https://github.com/jbanes) 
[fba-a320](https://github.com/pingflood/fba-a320/releases/latest/download/fba-a320.opk) | FB Alpha - Arcade and Console - A320 version | [@pingflood](https://github.com/pingflood) 
[fbasdl](https://github.com/pingflood/fba-sdl/releases/download/latest/fbasdl.ipk) | FB Alpha - Arcade and Console - GCW0 version | [@pingflood](https://github.com/pingflood)
[fceux](https://github.com/pingflood/fceux/releases/latest/download/fceux.opk) | NES | [@pingflood](https://github.com/pingflood) 
[gngeo](https://github.com/jbanes/gngeo/releases/latest) | NeoGeo | [@jbanes](https://github.com/jbanes/gngeo) 
[gpsp](https://github.com/pingflood/gpsp/releases/download/latest/gpsp.ipk) | Game Boy Advance | [@pingflood](https://github.com/pingflood/gpsp) 
[gambatte](https://github.com/bardeci/dot-matrix-simulator/releases/latest) | Game Boy / Game Boy Color | [@hi-ban](https://github.com/bardeci/dot-matrix-simulator) 
[handy](https://github.com/retrofw/handy/releases/download/latest/handy.ipk) | Atari Lynx | [@gameblabla](https://github.com/gameblabla) 
[jzintv](https://github.com/pingflood/jzintv/releases/download/latest/jzintv.ipk) | Intellivision | [@pingflood](https://github.com/pingflood/jzintv) 
[mame4all](https://gitlab.com/bopbopbopbop/mame4all-rs97/tags/) | MAME / Arcade | [@bopbopbopbop](https://gitlab.com/bopbopbopbop/mame4all-rs97) 
[openbor](https://github.com/retromsx/retrofw_ipks/releases/latest/download/openbor.ipk) | Open BOR | [@retromsx](https://github.com/retromsx) 
[oswan](https://github.com/retrofw/oswan/releases/download/latest/oswan.ipk) | WonderSwan | [@gameblabla](https://github.com/gameblabla) 
[pcsx4all](https://github.com/pingflood/pcsx4all/releases/latest/download/pcsx4all.opk) | Playstation (PSOne) | [@pingflood](https://github.com/pingflood/) 
[picodrive](https://github.com/pingflood/picodrive/releases/download/latest/picodrive.ipk) | Mega Drive / Sega CD / Master System / Game Gear | [@pingflood](https://github.com/pingflood/picodriv) 
[pocketsnes](https://github.com/pingflood/PocketSNES/releases/download/latest/pocketsnes.ipk) | Super NES | [@pingflood](https://github.com/pingflood/PocketSNES) 
[pokemini](https://github.com/pingflood/pokemini/releases/download/latest/pokemini.ipk) | PokéMini | [@pingflood](https://github.com/pingflood/pokemini) 
[prosystem-od](https://github.com/pingflood/prosystem-od/releases/download/latest/prosystem-od.ipk) | Atari 7800 | [@pingflood](https://github.com/pingflood/prosystem-od) 
[race-od](https://github.com/pingflood/race-od/releases/download/latest/race-od.ipk) | Neo Geo Pocket | [@pingflood](https://github.com/pingflood/race-od) 
[scummvm](https://github.com/jbanes/scummvm/releases/tag/2.1.0-RetroFW-RC5) | ScummVM | [@jbanes](https://github.com/jbanes/scummvm) 
[sms_sdl](https://github.com/retrofw/sms_sdl/releases/download/latest/sms_sdl.ipk) | Master System / Game Gear | [@gameblabla](https://github.com/gameblabla) 
[speccy](https://github.com/pingflood/speccy/releases/download/latest/speccy.ipk) | ZX Spectrum | [@pingflood](https://github.com/pingflood/speccy) 
[temper](https://github.com/retrofw/temper/releases/download/latest/temper.ipk) | PC-Engine | [@gameblabla](https://github.com/gameblabla) 
[uae4all](https://github.com/retrofw/uae4all/releases/download/latest/uae4all.ipk) | Amiga | [@pingflood](https://github.com/retrofw/uae4all) 
[vice](https://github.com/retrofw/vice/releases/download/latest/vice.ipk) | Commodore 64 | [@gameblabla](https://github.com/gameblabla) 
[potator](https://github.com/turtleletortue/potator/releases/download/1.1-0/potator.ipk) | Watara Supervision | [@turtleletortue](https://github.com/turtleletortue)

### Ports

Download | Title | Dev / Port by
:------:|:------|:------:
[abbaye](https://github.com/retrofw/abbaye/releases/download/latest/abbaye.ipk) | l'Abbaye des Morts | [@gameblabla](https://github.com/gameblabla) 
[apricots](https://github.com/retrofw/apricots/releases/download/latest/apricots.ipk) | Apricots | [@pingflood](https://github.com/retrofw/apricots) 
[arkanoid](https://github.com/retrofw/arkanoid/releases/download/latest/arkanoid.ipk) | Arkanoid | [@pingflood](https://github.com/retrofw/arkanoid) 
[blockout2](https://github.com/pingflood/blockout2/releases/download/latest/blockout2.ipk) | BlockOut 2 | [@pingflood](https://github.com/pingflood/blockout2)
[cannonball](https://github.com/retrofw/cannonball/releases/download/latest/cannonball.ipk) | The Enhanced OutRun Engine | [@gameblabla](https://github.com/gameblabla) 
[cavestory](https://github.com/retrofw/cavestory/releases/download/latest/cavestory.ipk) | Cave Story | [@pingflood](https://github.com/retrofw/cavestory)
[chocolate-doom](https://github.com/retrofw/chocolate-doom/releases/download/latest/chocolate-doom.ipk) | Chocolate Doom | [@gameblabla](https://github.com/gameblabla) 
[Circuit Dude](http://crait.net/download.php?file=CircuitDudeLDK.zip) | Circuit Dude | [@crait](http://crait.net/) 
[czdoom](https://github.com/scooterpsu/czdoom/releases/download/latest/czdoom.ipk) | CZDoom | [@scooterpsu](https://github.com/scooterpsu/czdoom) 
[DevilutionX](https://github.com/glebm/devilutionX/releases/download/0.5.0.300/devilutionx-retrofw.ipk) | DevilutionX (Diablo 1) | [@glebm](https://github.com/glebm/devilutionX/) 
[eduke32](https://github.com/retrofw/eduke32/releases/download/latest/eduke32.ipk) | Eduke32 (Duke Nukem 3D) | [@pingflood](https://github.com/retrofw/eduke32) 
[ganbare](https://github.com/retrofw/Ganbare-Natsuki-San/releases/download/latest/ganbare.ipk) | Ganbare-Natsukisan | [@gameblabla](https://github.com/gameblabla) 
[hcl](https://github.com/retrofw/hydracastlelabyrinth/releases/download/latest/hcl.ipk) | Hydra Castle Labyrinth | [@pingflood](https://github.com/retrofw/hydracastlelabyrinth) 
[hocoslamfy](https://github.com/scooterpsu/hocoslamfy/releases/download/latest/hocoslamfy.opk) | Hocoslamfy | [@scooterpsu](https://github.com/scooterpsu/hocoslamfy) 
[homingfever](https://github.com/retrofw/homingfever/releases/download/latest/homingfever.ipk) | Homing Fever | [@pingflood](https://github.com/retrofw/retrofw/homingfever) 
[jinyoung](https://github.com/guangmingwan/rs97-jy/releases) | Jin Yong Legend (Chinese game) | [@guangmingwan](https://github.com/guangmingwan/rs97-jy) 
[just4qix](https://github.com/retrofw/just4qix/releases/download/latest/just4qix.ipk) | Just4Qix | [@pingflood](https://github.com/retrofw/just4qix)
[kof](https://github.com/retrofw/bennugd/releases/download/kof/kof.ipk) | KOF Flames Of Courage | [@steward-fu](https://github.com/retrofw/bennugd) 
[liero](https://github.com/pingflood/liero/releases/download/latest/liero.ipk) | Liero | [@pingflood](https://github.com/pingflood/liero) 
[meritous](https://github.com/retrofw/meritous/releases/download/latest/meritous.ipk) | Meritous | [@pingflood](https://github.com/retrofw/meritous) 
[Midnight Wild](http://crait.net/download.php?file=MidnightWildLDK.zip) | Midnight Wild | [@crait](http://crait.net/) 
[mrdrillux](https://github.com/retrofw/mrdrillux/releases/download/latest/mrdrillux.ipk) | Mr Drillux | [@jbanes](https://github.com/jbanes) 
[openjazz](https://github.com/scooterpsu/OpenJazz/releases/download/latest/openjazz.opk) | OpenJazz (Jazz Jackrabbit) | [@scooterpsu](https://github.com/scooterpsu/OpenJazz) 
[opentyrian](https://github.com/retrofw/opentyrian/releases/download/latest/opentyrian.ipk) | Open Tyrian | [@gameblabla](https://github.com/gameblabla) 
[pang](https://github.com/retrofw/pang/releases/download/latest/pang.ipk) | Pang | [@pingflood](https://github.com/retrofw/pang) 
[profanation](https://github.com/retrofw/profanation/releases/download/latest/profanation.ipk) | Profanation Deluxe | [@pingflood](https://github.com/retrofw/profanation)
[quake](https://github.com/retrofw/quake/releases/download/latest/quake.ipk) | Quake | [@gameblabla](https://github.com/gameblabla) 
[quake2](https://github.com/retrofw/quake2/releases/download/latest/quake2.ipk) | Quake 2 | [@gameblabla](https://github.com/gameblabla) 
[REminiscence](https://github.com/scooterpsu/REminiscence/releases/download/latest/reminiscence.ipk) | REminiscence | [@scooterpsu](https://github.com/scooterpsu) 
[rockbot](https://github.com/retrofw/rockbot/releases/download/latest/rockbot.ipk) | Rockbot | [@pingflood](https://github.com/retrofw/rockbot) 
[rott](https://github.com/scooterpsu/rott-rs97/releases/) | Rise Of The Triad | [@scooterpsu](https://github.com/scooterpsu/rott-rs97/releases/)
[sorr](https://github.com/retrofw/bennugd/releases/download/sorr/sorr.ipk) | Streets of Rage Remake | [@steward-fu](https://github.com/retrofw/bennugd) 
[shifty](https://github.com/retrofw/shifty/releases/download/latest/shifty.ipk) | Shifty-Pills | [@pingflood](https://github.com/retrofw/shifty/releases) 
[smw](https://github.com/retrofw/smw/releases/download/latest/smw.ipk) | Super Mario War | [@pingflood](https://github.com/retrofw/smw) 
[spout](https://github.com/retrofw/spout/releases/download/latest/spout.ipk) | Spout | [@pingflood](https://github.com/retrofw/spout) 
[srb2](https://github.com/retrofw/srb2/releases/download/latest/srb2.ipk) | Sonic Robo Blast 2 | [@pingflood](https://github.com/retrofw/srb2/releases)
[stransball2](https://github.com/retrofw/stransball2/releases/download/latest/stransball2.ipk) | Super Transball 2 | [@pingflood](https://github.com/retrofw/stransball2)
[tileworld](https://github.com/retrofw/tileworld/releases/download/latest/tileworld.ipk) | Tile World | [@pingflood](https://github.com/retrofw/tileworld) 
[wolf3d](https://github.com/scooterpsu/wolf3d/releases) | Wolfenstein 3D and Spear of Destiny | [@scooterpsu](https://github.com/scooterpsu/wolf3d) 
[zelda_roth](https://github.com/retrofw/zelda_roth/releases/download/latest/zelda_roth.ipk) | The Legend of Zelda - Return of the Hylian | [@pingflood](https://github.com/retrofw/zelda_roth) 
[xrick](https://github.com/scooterpsu/xrick/releases/download/latest/xrick.opk) | xRick (Rick Dangerous) | [@scooterpsu](https://github.com/scooterpsu/xrick) 
