<img src="https://retrogamecorps.files.wordpress.com/2021/02/simple30.png">

# Simple30
The goal of Simple30 is to give the user a fully capable device, but with a pick-up-and-play experience, on the PocketGo S30.  This project is a continuation of my previous <a href="https://github.com/retrogamecorps/s30-add-on-pack">S30 Add-On Pack</a>, thanks to a number of developers whose work enabled me to compile and streamline the user experience.

### Credit:

<a href="https://github.com/bkacjios">bkacjois</a> was able to create a fully-formed RetroArch 1.9.0 that works on the S30<br>
<a href="https://github.com/slaminger">slaminger</a> added dozens of new emulators and ports to the device<br>
DaMikki developed a safe shutdown mechanism for use with this device<br>

## Features

### Simple30 is:

- Optimized to allow you to play 90 systems and ports altogether, but the flexibility to pare down your system list to as few systems as you’d like (or as many as you’d like).
- Pre-configured with optimal graphics settings to give you an excellent viewing experience without having to tinker with the settings yourself (but with the freedom to tinker if you’d like).
- Pre-loaded with all relevant shaders and cheat files for your viewing and gaming pleasure.
- Pre-configured with hotkeys to allow you to quickly and efficiently navigate your games.
- Able to use a safe shutdown mechanism that allows you to safely power off your device and preserve your save games and configuration settings.

## Installation

I recommend you upgrade the stock SD card in your device to a 128GB or 256GB microSD card, from a reputable brand like SanDisk or Samsung, so that you have a reliable storage option with plenty of space for your game collection. It is also confirmed that 512GB cards also work fine on this device. <a href="https://retrogamecorps.com/shop/#Cards">Here is a link to my recommended cards.</a>

In order for this card to work on your device, you will need to format it to FAT32 file system. Windows can only format cards which are less than 32GB to FAT32, so you will need to use a program called <a href="https://gbatemp.net/download/gui-format.33869/">guiformat</a>. For Mac, you can use the Disk Utility program that comes with MacOS to format (“erase”) the card, with MS-DOS (FAT) as the format. In both cases, you can name the card “SIMPLE30”.

Once your card is formatted, download Simple30 here:

### >> <a href="https://drive.google.com/file/d/1-nnvOmx13_mVMazezN-XzuV_GDc-6F85/view?usp=drivesdk">Simple30 on Google Drive</a>

Unzip the contents and drag them into your FAT32-formatted SD card. That’s it, you’re done. You can now add your game files to their respective folder within the main “roms” folder, and your BIOS files, too (more on that in the next section).

## Required BIOS files

The BIOS files now need to be placed in the retroarch/system folder. Here are the necessary BIOS files for the default systems:

DREAMCAST:<br>
dc/dc_boot.bin<br>
dc/dc_flash.bin<br>

SEGA CD:<br>
bios_CD_E.bin<br>
bios_CD_J.bin<br>
bios_CD_U.bin<br>

FAMICOM DISK SYSTEM:<br>
disksys.rom<br>

GAME BOY (for boot logo):<br>
gb_bios.bin<br>

GAME BOY COLOR (for boot logo):<br>
gbc_bios.bin<br>

GAME BOY ADVANCE:<br>
gba_bios.bin<br>

NEO GEO:<br>
neogeo.zip<br>

PLAYSTATION:<br>
scph1001.bin<br>

TURBOGRAFX-CD:<br>
syscard1.pce<br>
syscard2.pce<br>
syscard3.pce<br>

## Supported systems

The Simple30 image, by default, contains about 20 of the most popular classic systems:

Arcade (FinalBurn Neo)<br>
Arcade (MAME 2003-Plus)<br>
Arcade (Neo Geo)<br>
Nintendo Entertainment System<br>
Super NES<br>
Nintendo 64<br>
Game Boy<br>
Game Boy Color<br>
Game Boy Advance<br>
Sega Master System<br>
Sega Genesis<br>
Sega CD<br>
Sega 32X<br>
Sega Dreamcast<br>
Sega Game Gear<br>
Sony PlayStation<br>
Sony PSP<br>
TurboGrafx-16<br>
TurboGrafx-CD<br>

Note that with this new software, Nintendo 64 is now available. But just like Sega Dreamcast and Sony PSP, performance is relatively limited. The other systems play just fine.

If you want to remove any of these systems from your main menu, simply go to the sections/emulators folder on your SD card, and move the respective system launcher file (they’ll be labeled according to the system they support) into the sections/emulators/optional folder; this will make the system disappear from your main menu.

But additionally, there are other emulators and ports that you can play on your device, such as:

CPS1<br>
CPS2<br>
MAME 2003<br>
MAME 2010<br>
Neo Geo CD<br>
Famicom Disk System<br>
Famicom<br>
MSU1<br>
Satellaview<br>
Super Famicom<br>
Sufami Turbo<br>
N64DD<br>
N64 (Parallel core)<br>
Virtual Boy<br>
Game & Watch<br>
Super Game Boy<br>
Atomiswave<br>
Naomi<br>
Dreamcast VMU<br>
PSP Minis<br>
Neo Geo Pocket<br>
Neo Geo Pocket Color<br>
Atari Lynx<br>
Wonderswan<br>
Wonderswan Color<br>
ZX Spectrum<br>
TIC-80<br>
MSX Turbo R<br>
MSX<br>
MSX2<br>
Colecovision<br>
Odyssey Videopac<br>
SuperGrafx<br>
SG-1000<br>
Atari 2600<br>
Atari 5200<br>
Atari 800<br>
Atari 78<br>
Atari ST<br>
Vectrex<br>
Amiga 500<br>
Amiga CD32<br>
PC98<br>
PC88<br>
Channel F<br>
X86000<br>
Sharp X1<br>
Amstrad CPC<br>
Intellivision<br>
Thomas MO5<br>
Commodore 64<br>
Commodore 128<br>
Commodore PET<br>
Commodore Plus4<br>
Commodore VIC20<br>
Palm OS<br>
2048<br>
EasyRPG<br>
Pokemon Mini<br>
Wolfenstein 3D<br>
Mr. Boom<br>
Uzebox<br>
Cavestory<br>
Quake<br>
Lutro<br>
Rick Dangerous<br>
DOOM<br>
OutRun<br>
Dinothawr<br>

To add these systems to your device, navigate to the sections/emulators/optional/ folder, and move whatever system you would like to play into the sections/emulators folder instead. Note that some of these systems will require additional BIOS files, and the ports will require retail files added to their respective rom folder.

## Hotkeys

All of the emulators (except for the standalone PSP emulator) will take advantage of RetroArch’s universal hotkeys system. Here are the hotkeys that you can use while in a game:

### RetroArch hotkeys

SELECT + POWER = Quit game and return to main menu<br>
SELECT + START = RetroArch Menu<br>
Hold START (3 seconds) = RetroArch Menu<br>
SELECT + Y = Toggle FPS (frames per second)<br>
SELECT + B = reset game<br>
SELECT + A = pause emulation<br>
SELECT + R1 = save state<br>
SELECT + L1 = load save state<br>
SELECT + L2 = rewind (when enabled)<br>
SELECT + R2 = fast forward (currently no working)<br>
SELECT + RIGHT on d-pad = save state slot +<br>
SELECT + LEFT on d-pad = save state slot -<br>
SELECT + UP on d-pad = volume up<br>
SELECT + DOWN on d-pad = volume down<br>

## Notes

Here are some random notes that may help you get the most out of this unique device:

- If you load your roms onto your SD card and do not see them in the menu, go into the sections/emulators folder on your SD card and find the appropriate launcher file for your system.  Open that file with a text editor, and find that last bit of code: (`selectorfilter=gdi,cdi`) or similar, and add the file extensions of your roms (.iso, .img, and so on).
- To scrape boxart or videos for your menus, <a href="https://retrogamecorps.com/2021/01/08/pocketgo-s30-starter-guide/#Boxart">check out this section of my Starter Guide.</a>
You can adjust the brightness within RetroArch by going to Settings > Video > Output > Screen Brightness. I find this easier than closing out of the game and adjusting the brightness in the main menu.
- With the way the system is currently configured, you cannot switch between RetroArch cores in one system. For example, while most Nintendo 64 games play best with the Mupen64Plus N64 emulator, others may play better with the Parallel N64 core. There isn’t a way to set the Parallel N64 core to launch with certain games. Instead, I’ve made a Parallel N64 core section, so that you can launch the same N64 library with that core instead. To set it up, go into the sections/emulators/optional folder on your SD card, and move the file named “07 parallel (n64)” into the sections/emulators folder. Now you will see a Parallel N64 option in your main menu.
- If you would rather just run RetroArch by default and not deal with the Simple30 menu interface, that is set up as well. Go into the bin/RA launcher folder on your SD card, and move the gmenu2x from from that folder into the bin folder (replace the one that’s already in there, although I would make a backup in case you want to revert back at some point). From now on you will launch directly into RetroArch whenever you boot up the device, and quitting RetroArch will shut down the device.

## Known issues

Like any software solution, Simple30 is a work in progress. Here are some of the issues that I have noted:

- The “Save Content Directory Overrides” function does not work, which means that you cannot save settings specific to one game folder for systems that use the same core. For example, you cannot save Game Gear specific settings because it shares the same core as Master System, Genesis, and Sega CD.
- Some shaders will rotate the screen when turned on.
- Fast forward function does not work at this time.
- Volume and brightness levels are reset when the device is powered off/on.
- With MAME2003-Plus, some button presses register as multiple buttons.  Until a fix is in place, you can do a workaround by swapping out the RetroArch core with MAME2003 (open the sections/emulators/ folder, find the MAME 2003-Plus file, open it with a text editor, and change the core to (`params=-v -c retroarch-arcade.cfg -L mame2003_libretro.so`).
