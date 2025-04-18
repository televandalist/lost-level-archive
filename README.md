**Note: I am aware of the inconsistencies in the naming scheme for some consoles. I plan to fix this after I've had time to do some more research.**

![lostlevelarchive](https://github.com/televandalist/lost-level-archive/assets/45054151/80332816-29b5-4011-aed0-e06e68ae08b6)

### Project Information

First off, if you're not familiar with how DATs work, then this project will not be of much use to you. A great explanation already exists on [ROMVault's wiki page](https://wiki.romvault.com/doku.php?id=supported_dats).

Since late-2018, I have been the "hash and patch" guy at [RetroAchievements.org](https://retroachievements.org). For those who don't know, specific hashes (aka the "correct" ROM) of games are required to load and earn achievements. Each game has a "Supported Game Files" page which lists the ROMs that are compatible with its set. Here's the page for [Jack Bros. for Virtual Boy](https://retroachievements.org/game/11700/hashes) as an example. I maintain the database for these and am responsible for making sure each hash is verified and correctly labeled. The majority of these match info found in the DATs for [No Intro](https://datomatic.no-intro.org/), [Redump](http://redump.org/downloads/), [Final Burn Neo](https://github.com/libretro/fbneo/tree/master/dats), [TOSEC](https://www.tosecdev.org/downloads), among others. More info on the hash labels can be found in the RetroAchievements Docs [section about hash labels](https://docs.retroachievements.org/guidelines/content/hash-labels.html#hash-labels). Some labels are not tied to particular DATs and are mostly just generic labels. These include `homebrew`, `itchio`, `msu1`, etc.

In January 2021, I started the [RAPatches repository](https://github.com/RetroAchievements/RAPatches) with the intent to preserve patches to be used with No Intro and Redump bases that result in ROMs whose hashes match those linked on RetroAchievements.org.

RAPatches has been tremendously helpful in getting RetroAchievements' hash database organized by taking care of most of the hacks, translations, bug fixes, etc.

To further improve and organize things, I joined No Intro as a dumper. So far, I've submitted info for over 600 ROMs that were added to No Intro's DATs. This allowed me to switch the hash labels over to No Intro for those ROMs, which I find very satisfying, albeit very time-consuming.

However, there are many "other" hashes without a proper home within a DAT. These include many homebrews, bootlegs, oddball extractions (such as ripping GBA ROMs from a GameCube disc for [Crash Bandicoot Blast!](https://retroachievements.org/game/17408/hashes)), betas, demos, prototypes, etc. A lot of these could be submitted to No Intro and Redump, but it would take **a lot** of time to do considering the amount of information that's required for submissions and with how often new hashes are linked to RetroAchievements. Additionally, there are many hacks, fixes, translations, undubs, etc. that are not feasible to add to RAPatches. This is usually due to the size of the patches, but there are other reasons to not do it, which I won't get into here.

I started **Lost Level Archive** as a way to give those "other" hashes a home without any red tape. I can add to it as often as I want and obviously the hashes need to be verified in order for them to appear. It's a win-win.

*tl;dr = You know how No Intro has the Non-Redump DAT for stuff that isn't DAT'd by Redump? This is similar, but for both No Intro and Redump.*

### Ongoing and Future Plans
In addition to getting RetroAchievement's "other" hashes into a DAT, I'm either currently doing or plan to do the following:
- A supplementary "Extras" DAT for [DOSBox Pure's DAT project](https://github.com/PureDOS/DAT). This DAT contains manuals, reference guides, and other extras that you can usually find on GOG, eXoDOS, MyAbandonWare, etc. I originally wanted to add them to the DOSBox Pure DAT, but that wasn't the right fit for them. This is ongoing and found [here](https://github.com/televandalist/lost-level-archive/blob/main/Extra/DOSBox%20Pure%20Extras/Lost%20Level%20Archive%20-%20PureDOSDAT_Extras.xml).
- Provide GDI and CUE files for disc images that appear in the **Lost Level Archive** DATs. You know, to make things slightly more convenient.
- Provide ***public domain*** ROMs where able, utilizing the naming scheme used for **Lost Level Archive**, **RAPatches**, etc., which is inspired by **No Intro**'s naming scheme.
- Fully DAT 4am's `4am Crack` and `Woz-A-Day` projects for Apple IIe.
- For any ROMs that are linked to RetroAchievements via an RA Hash, DAT them with the actual proper info.

### ID Numbers
You may have noticed that the filenames of the DATs start with numbers that don't follow a discernable pattern. These are the Console ID numbers for RetroAchievements.org. Here is the full list:
| ID Number | Manufacturer/Developer | Console/Platform |
| :-------: | ---------------------- | ------- |
| 01 | Sega | Mega Drive - Genesis |
| 02 | Nintendo | Nintendo 64 |
| 03 | Nintendo | Super Famicom - SNES |
| 04 | Nintendo | Game Boy |
| 05 | Nintendo | Game Boy Advance |
| 06 | Nintendo | Game Boy Color |
| 07 | Nintendo | Famicom - NES |
| 08 | NEC | PC Engine - TurboGrafx-16 |
| 09 | Sega | Sega CD |
| 10 | Sega | 32X |
| 11 | Sega | Master System |
| 12 | Sony | PlayStation |
| 13 | Atari | Lynx |
| 14 | SNK | Neo Geo Pocket Color |
| 15 | Sega | Game Gear |
| 16 | Nintendo | GameCube |
| 17 | Atari | Jaguar |
| 18 | Nintendo | Nintendo DS |
| 19 | Nintendo | Wii |
| 20 | Nintendo | Wii U |
| 21 | Sony | PlayStation 2 |
| 22 | Microsoft | Xbox |
| 23 | Magnavox | Odyssey2 |
| 24 | Nintendo | Pokemon Mini |
| 25 | Atari | Atari 2600 |
| 26 | Microsoft | DOS |
| 27 | N/A | Arcade |
| 28 | Nintendo | Virtual Boy |
| 29 | Microsoft | MSX |
| 30 | Commodore | Commodore 64 |
| 31 | Sinclair | ZX81 |
| 32 | Tangerine | Oric |
| 33 | Sega | SG-1000 |
| 34 | Commodore | Vic-20 |
| 35 | Commodore | Amiga |
| 36 | Atari | Atari ST |
| 37 | Amstrad | Amstrad CPC |
| 38 | Apple | Apple II |
| 39 | Sega | Saturn |
| 40 | Sega | Dreamcast |
| 41 | Sony | PlayStation Portable |
| 42 | Philips | CD-i |
| 43 | 3DO Company | 3DO |
| 44 | Coleco | ColecoVision |
| 45 | Mattel | Intellivision |
| 46 | GCE | Vectrex |
| 47 | NEC | PC-8000/PC-8800 |
| 48 | NEC | PC-9800 |
| 49 | NEC | PC-FX |
| 50 | Atari | Atari 5200 |
| 51 | Atari | Atari 7800 |
| 52 | Sharp | X86000 |
| 53 | Bandai | WonderSwan Color |
| 54 | Epoch | Cassette Vision |
| 55 | Epoch | Super Cassette Vision |
| 56 | SNK | Neo Geo CD |
| 57 | Fairchild | Channel F |
| 58 | Fujitsu | FM Towns |
| 59 | Sinclair | ZX Spectrum |
| 60 | Nintendo | Game & Watch |
| 61 | Nokia | N-Gage |
| 62 | Nintendo | Nintendo 3DS |
| 63 | Watara | Supervision |
| 64 | Sharp | X1 |
| 65 | Nesbox | TIC-80 |
| 66 | Thomson | TO8 |
| 67 | NEC | PC-6000 |
| 68 | Sega | Pico |
| 69 | Welback | Mega Duck |
| 70 | Zeebo Inc | Zeebo |
| 71 | Arduboy Inc | Arduboy |
| 72 | Aduros | WASM-4 |
| 73 | Emerson | Arcadia 2001 |
| 74 | Interton | VC 4000 |
| 75 | Elektor | TV Games Computer |
| 76 | NEC | PC Engine CD - TurboGrafx-CD |
| 77 | Atari | Jaguar CD |
| 78 | Nintendo | Nintendo DSi |
| 79 | Texas Instruments | TI-83 |
| 80 | Belogic Software | Uzebox |

### Contributing
I will chip away at a proper guide for this. In the meantime, if you would like to help, contact me via [RetroAchievements](https://retroachievements.org/user/tele) or via Discord `@televandalist`. 

### Links
- [RetroAchievements.org](https://retroachievements.org)
- [RAPatches](https://github.com/RetroAchievements/RAPatches) - patch repository for RetroAchievements
- [RAHashes](https://github.com/RetroAchievements/RAHashes) - repository containing ongoing lists of hashes exclusive to RetroAchievements
- [PureDOS DAT](https://github.com/PureDOS/DAT) - DOSBox Pure DAT project, which is a prerequisite for DOS support on RetroAchievements
- [Clean CPC DB](https://github.com/clean-cpc-db) - DAT Project for Amstrad CPC, which was put together by D_Skywalk when he was helping us support it.
- [ROMVault](https://www.romvault.com/) - preferred ROM manager
- [SabreTools](https://github.com/SabreTools/SabreTools) - DAT management tool that I use to make the DATs found here
