# Simple30
When it comes down to it, the goal of Simple30 is to give the user a fully capable device, but with a pick-up-and-play experience.

This project is available thanks to a number of developers whose work enabled me to basically compile and streamline the user experience.

bkacjois was able to create a fully-formed RetroArch 1.9.0 that works on the S30
slaminger added dozens of new emulators and ports to the device
DaMikki developed a safe shutdown mechanism for use with this device

## Features

Simple30 is:

- Optimized to allow you to play 90 systems and ports altogether, but the flexibility to pare down your system list to as few systems as you’d like (or as many as you’d like).
- Pre-configured with optimal graphics settings to give you an excellent viewing experience without having to tinker with the settings yourself (but with the freedom to tinker if you’d like).
- Pre-loaded with all relevant shaders and cheat files for your viewing and gaming pleasure.
- Pre-configured with hotkeys to allow you to quickly and efficiently navigate your games.
- Able to use a safe shutdown mechanism that allows you to safely power off your device and preserve your save games and configuration settings.

## Installation

I recommend you upgrade the stock SD card in your device to a 128GB or 256GB microSD card, from a reputable brand like SanDisk or Samsung, so that you have a reliable storage option with plenty of space for your game collection. It is also confirmed that 512GB cards also work fine on this device. Here is a link to my recommended cards.

In order for this card to work on your device, you will need to format it to FAT32 file system. Windows can only format cards which are less than 32GB to FAT32, so you will need to use a program called guiformat. For Mac, you can use the Disk Utility program that comes with MacOS to format (“erase”) the card, with MS-DOS (FAT) as the format. In both cases, you can name the card “SIMPLE30”.

Once your card is formatted, download Simple30 here:

Simple30 on Google Drive

Unzip the contents and drag them into your FAT32-formatted SD card. That’s it, you’re done. You can now add your game files to their respective folder within the main “roms” folder, and your BIOS files, too (more on that in the next section).

## Required BIOS files

The BIOS files now need to be placed in the retroarch/system folder. Here are the necessary BIOS files for the default systems:

DREAMCAST: 
dc/dc_boot.bin
dc/dc_flash.bin

SEGA CD:
bios_CD_E.bin
bios_CD_J.bin
bios_CD_U.bin

FAMICOM DISK SYSTEM:
disksys.rom

GAME BOY (for boot logo):
gb_bios.bin

GAME BOY COLOR (for boot logo):
gbc_bios.bin

GAME BOY ADVANCE:
gba_bios.bin

NEO GEO:
neogeo.zip

PLAYSTATION:
scph1001.bin

TURBOGRAFX-CD:
syscard1.pce
syscard2.pce
syscard3.pce
Supported systems

The Simple30 image, by default, contains about 20 of the most popular classic systems:

Arcade (FinalBurn Neo)
Arcade (MAME 2003-Plus)
Arcade (Neo Geo)
Nintendo Entertainment System
Super NES
Nintendo 64
Game Boy
Game Boy Color
Game Boy Advance
Sega Master System
Sega Genesis
Sega CD
Sega 32X
Sega Dreamcast
Sega Game Gear
Sony PlayStation
Sony PSP
TurboGrafx-16
TurboGrafx-CD

Note that with this new software, Nintendo 64 is now available. But just like Sega Dreamcast and Sony PSP, performance is relatively limited. The other systems play just fine.

If you want to remove any of these systems from your main menu, simply go to the sections/emulators folder on your SD card, and move the respective system launcher file (they’ll be labeled according to the system they support) into the sections/emulators/optional folder; this will make the system disappear from your main menu.

But additionally, there are other emulators and ports that you can play on your device, such as:

CPS1
CPS2
MAME 2010
Neo Geo CD
Famicom Disk System
Famicom
MSU1
Satellaview
Super Famicom
Sufami Turbo
N64DD
N64 (Parallel core)
Virtual Boy
Game & Watch
Super Game Boy
Atomiswave
Naomi
Dreamcast VMU
PSP Minis
Neo Geo Pocket
Neo Geo Pocket Color
Atari Lynx
Wonderswan
Wonderswan Color
ZX Spectrum
TIC-80
MSX Turbo R
MSX
MSX2
Colecovision
Odyssey Videopac
SuperGrafx
SG-1000
Atari 2600
Atari 5200
Atari 800
Atari 78
Atari ST
Vectrex
Amiga 500
Amiga CD32
PC98
PC88
Channel F
X86000
Sharp X1
Amstrad CPC
Intellivision
Thomas MO5
Commodore 64
Commodore 128
Commodore PET
Commodore Plus4
Commodore VIC20
Palm OS
2048
EasyRPG
Pokemon Mini
Wolfenstein 3D
Mr. Boom
Uzebox
Cavestory
Quake
Lutro
Rick Dangerous
DOOM
OutRun
Dinothawr

To add these systems to your device, navigate to the sections/emulators/optional/ folder, and move whatever system you would like to play into the sections/emulators folder instead. Note that some of these systems will require additional BIOS files, and the ports will require retail files added to their respective rom folder.

## Hotkeys

All of the emulators (except for the standalone PSP emulator) will take advantage of RetroArch’s universal hotkeys system. Here are the hotkeys that you can use while in a game:

RetroArch hotkeys

SELECT + POWER = Quit game and return to main menu
SELECT + START = RetroArch Menu
Hold START (3 seconds) = RetroArch Menu
SELECT + Y = Toggle FPS (frames per second)
SELECT + B = reset game
SELECT + A = pause emulation
SELECT + R1 = save state
SELECT + L1 = load save state
SELECT + L2 = rewind (when enabled)
SELECT + R2 = fast forward (currently no working)
SELECT + RIGHT on d-pad = save state slot +
SELECT + LEFT on d-pad = save state slot -
SELECT + UP on d-pad = volume up
SELECT + DOWN on d-pad = volume down
Notes

## Notes

Here are some random notes that may help you get the most out of this unique device:

To scrape boxart or videos for your menus, check out this section of my Starter Guide.
You can adjust the brightness within RetroArch by going to Settings > Video > Output > Screen Brightness. I find this easier than closing out of the game and adjusting the brightness in the main menu.

With the way the system is currently configured, you cannot switch between RetroArch cores in one system. For example, while most Nintendo 64 games play best with the Mupen64Plus N64 emulator, others may play better with the Parallel N64 core. There isn’t a way to set the Parallel N64 core to launch with certain games. Instead, I’ve made a Parallel N64 core section, so that you can launch the same N64 library with that core instead. To set it up, go into the sections/emulators/optional folder on your SD card, and move the file named “07 parallel (n64)” into the sections/emulators folder. Now you will see a Parallel N64 option in your main menu.

If you would rather just run RetroArch by default and not deal with the Simple30 menu interface, that is set up as well. Go into the bin/RA launcher folder on your SD card, and move the gmenu2x from from that folder into the bin folder (replace the one that’s already in there, although I would make a backup in case you want to revert back at some point). From now on you will launch directly into RetroArch whenever you boot up the device, and quitting RetroArch will shut down the device.

## Known issues

Like any software solution, Simple30 is a work in progress. Here are some of the issues that I have noted:

- The “Save Content Directory Overrides” function does not work, which means that you cannot save settings specific to one game folder for systems that use the same core. For example, you cannot save Game Gear specific settings because it shares the same core as Master System, Genesis, and Sega CD.
- Some shaders will rotate the screen when turned on.
- Fast forward function does not work at this time.
- Volume and brightness levels are reset when the device is powered off/on.
