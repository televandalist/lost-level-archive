![lostlevelarchive](https://github.com/televandalist/lost-level-archive/assets/45054151/80332816-29b5-4011-aed0-e06e68ae08b6)

### Project Information

First off, if you're not familiar with how DATs work, then this project will not be of much use to you. A great explanation already exists on [ROMVault's wiki page](https://wiki.romvault.com/doku.php?id=supported_dats).

Since late-2018, I have been the "hash and patch" guy at [RetroAchievements.org](https://retroachievements.org). For those who don't know, specific hashes (aka the "correct" ROM) of games are required to load and earn achievements. Each game has a "Supported Game Files" page which lists the ROMs that are compatible with its set. Here's the page for [Jack Bros. for Virtual Boy](https://retroachievements.org/game/11700/hashes) as an example. I maintain the database for these and am responsible for making sure each hash is verified and correctly labeled. The majority of these match info found in the DATs for [No Intro](https://datomatic.no-intro.org/), [Redump](http://redump.org/downloads/), [Final Burn Neo](https://github.com/libretro/fbneo/tree/master/dats), [TOSEC](https://www.tosecdev.org/downloads), amoung others. More info on the hash labels can be found in the RetroAchievements Docs [section about hash labels](https://docs.retroachievements.org/guidelines/content/hash-labels.html#hash-labels). Some labels are not tied to particular DATs and are mostly just generic labels. These include `homebrew`, `itchio`, `msu1`, etc.

In early-2022, I started the [RAPatches repository](https://github.com/RetroAchievements/RAPatches) with two goals in mind:
- Preserve patches to be used with No Intro and Redump bases that result in ROMs whose hashes match those linked on RetroAchievements.org.
- Eliminate the need for the GoodTools label since it hasn't been updated in over a decade, has an awful naming scheme, and let's face it: is mostly trash that's pretty much just digital hoarding. I'll never understand the need to preserve bad dumps. 🤷‍♂️

RAPatches has been tremendously helpful in getting RetroAchievements' hash database organized by taking care of most of the hacks, translations, bug fixes, etc.

To further improve and organize things, I joined No Intro as a dumper. So far, I've submitted info for over 600 ROMs that were added to No Intro's DATs. This allowed me to switch the hash labels over to No Intro for those ROMs, which I find very satisfying, albeit very time-consuming.

However, there are many "other" hashes without a proper home within a DAT. These include many homebrews, bootlegs, oddball extractions (such as ripping GBA ROMs from a GameCube disc for [Crash Bandicoot Blast!](https://retroachievements.org/game/17408/hashes)), betas, demos, prototypes, etc. A lot of these could be submitted to No Intro and Redump, but it would take **a lot** of time to do considering the amount of information that's required for submissions and with how often new hashes are linked to RetroAchievements. Additionally, there are many hacks, fixes, translations, undubs, etc. that are not feasible to add to RAPatches. This is usually due to the size of the patches, but there are other reasons to not do it, which I won't get into here.

I started **Lost Level Archive** as a way to give those "other" hashes a home without any red tape. I can add to it as often as I want and obviously the hashes need to be verified in order for them to appear. It's a win-win.

### Ongoing and Future Plans
In addition to getting RetroAchievement's "other" hashes into a DAT, I'm either currently doing or plan to do the following:
- A supplementary "Extras" DAT for [DOSBox Pure's DAT project](https://github.com/PureDOS/DAT). This DAT contains manuals, reference guides, and other extras that you can usually find on GOG, eXoDOS, MyAbandonWare, etc. I originally wanted to add them to the DOSBox Pure DAT, but that wasn't the right fit for them. This is ongoing and found [here](https://github.com/televandalist/lost-level-archive/blob/main/Extra/DOSBox%20Pure%20Extras/Lost%20Level%20Archive%20-%20PureDOSDAT_Extras.xml).
- Provide GDI and CUE files for disc images that appear in the **Lost Level Archive** DATs. You know, to make things slightly more convenient.
- Provide ***public domain*** ROMs where able, utilizing the naming scheme used for **Lost Level Archive**, **RAPatches**, etc., which is inspired by **No Intro**'s naming scheme.
- Fully DAT 4am's `4am Crack` and `Woz-A-Day` projects for Apple IIe.
- For any ROMs that are linked to RetroAchievements via an RA Hash, DAT them with the actual proper info.

### Contributing
I will chip away at a proper guide for this. In the meantime, if you would like to help, contact me via [RetroAchievements](https://retroachievements.org/user/televandalist) or via Discord `@televandalist`. 

### Links
- [RetroAchievements.org](https://retroachievements.org)
- [RAPatches](https://github.com/RetroAchievements/RAPatches) - patch repository for RetroAchievements
- [RAHashes](https://github.com/RetroAchievements/RAHashes) - repository containing ongoing lists of hashes exclusive to RetroAchievements
- [PureDOS DAT](https://github.com/PureDOS/DAT) - DOSBox Pure DAT project, which is a prerequisite for DOS support on RetroAchievements
- [Clean CPC DB](https://github.com/clean-cpc-db) - DAT Project for Amstrad CPC, which was put together by D_Skywalk when he was helping us support it.
- [ROMVault](https://www.romvault.com/) - preferred ROM manager
- [SabreTools](https://github.com/SabreTools/SabreTools) - DAT management tool that I use to make the DATs found here
