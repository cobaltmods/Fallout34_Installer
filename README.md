# Fallout 34 Installer

## Intro

Fallout 3 and New Vegas are now playable inside of Fallout 4, alongside Fallout 4.

[Join my modding discord here](https://discord.com/invite/hQAMQbH3MQ)

We do not ship ANY game files as part of this. Zero! This is just a standalone converter that will convert your local fallout 3 and nv files into your local fallout 4 files. You must own and install both games yourself for this to work, and then run the installer which can take ~2 hours to convert everything. This is the only way we can distribute the mod legally.

## Requirements

### Required

| Mod name | Notes |
| --- | --- |
| [Fallout 3 + All DLC](https://store.steampowered.com/app/22370/Fallout_3_Game_of_the_Year_Edition/) | Required |
| [Fallout 4 + All DLC](https://store.steampowered.com/app/377160/Fallout_4/) | Required |
| [Fallout NV + All DLC](https://store.steampowered.com/app/22380/Fallout_New_Vegas/) | Required |
| [FO4 - Address Library for F4SE Plugins](https://www.nexusmods.com/fallout4/mods/47327) | Required |
| [FO4 - Backpacks of the Commonwealth](https://www.nexusmods.com/fallout4/mods/29447) | Required |
| [FO4 - Buffout 4 NG and VR](https://www.nexusmods.com/fallout4/mods/64880) | Required |
| [FO4 - Extended Dialogue Interface](https://www.nexusmods.com/fallout4/mods/27216) | Required |
| [FO4 - Fallout 4 Script Extender (F4SE)](https://www.nexusmods.com/fallout4/mods/42147) | Required |
| [FO4 - FallUI - Inventory](https://www.nexusmods.com/fallout4/mods/48758) | Required (do not use M8rDisablePipboyEffects) |
| [FO4 - High FPS Physics Fix](https://www.nexusmods.com/fallout4/mods/44798) | Required |
| [FO4 - LevelUpMenuEx](https://www.nexusmods.com/fallout4/mods/28822) | Required |
| [FO4 - Mod Configuration Menu](https://www.nexusmods.com/fallout4/mods/21497) | Required |
| [FO4 - Screen Space Reflections (SSR) Fixes by Cobalt](https://www.nexusmods.com/fallout4/mods/110081) | Required |
| [FNV - Interior Lighting Overhaul](https://www.nexusmods.com/newvegas/mods/35794?tab=files) | Required |
| [FNV - Mesh Improvement Mod](https://www.nexusmods.com/newvegas/mods/74295) | Required |
| [FO3 - ATMOS Interior lighting overhaul](https://www.nexusmods.com/fallout3/mods/25911) | Required |
| [FO3 - DC Interiors](https://www.nexusmods.com/fallout3/mods/5573) | Required |
| [FO3 - Street Lights](https://www.nexusmods.com/fallout3/mods/8069?tab=files) | Required |
| [Reshade](https://reshade.me/) | Required (with addon support) (empty is fine) |

### Optional but recommended

| Mod name | Notes |
| --- | --- |
| [FO4 - Campsite - Simple Wasteland Camping (and HD Sleeping Bags)](https://www.nexusmods.com/fallout4/mods/11734) | Optional but recommended |
| [FO4 - More Grass](https://www.nexusmods.com/fallout4/mods/2310) | Optional but recommended |
| [FO4 - No More Screen Blur When Hit](https://www.nexusmods.com/fallout4/mods/5777) | Optional but recommended |
| [FO4 - Power Armor Classic Green Interface](https://www.nexusmods.com/fallout4/mods/73476) | Optional but recommended |
| [FO4 - REACTOR - A FALLOUT4 ENB](https://www.nexusmods.com/fallout4/mods/57321) | Optional but recommended |
| [FO4 - Screen Flicker Killer and no blur effect](https://www.nexusmods.com/fallout4/mods/3191) | Optional but recommended |
| [FO4 - Synth Mules - On-demand delivery](https://www.nexusmods.com/fallout4/mods/109971) | Optional but recommended |
| [FO4 - True Storms - Wasteland Edition (Thunder-Rain-Weather Redone)](https://www.nexusmods.com/fallout4/mods/4472) | Optional but recommended |
| [FO4 - Upscaling Custom - DLSS 5 FSR XeSS FG Full ENB Support](https://www.nexusmods.com/fallout4/mods/108772) | Optional but recommended |
| [FO4 - Vivid Weathers - Fallout 4 Edition - a Weather Mod and Climate Overhaul](https://www.nexusmods.com/fallout4/mods/15466) | Optional but recommended |
| [FO4 - Weather Synergy - True Storms 2.x patch](https://www.nexusmods.com/fallout4/mods/97986) | Optional but recommended |
| [FO4 - Weather Synergy - True Storms and Vivid Weathers merge patch](https://www.nexusmods.com/fallout4/mods/15908) | Optional but recommended |
| [Fallout 34 Online](https://www.nexusmods.com/fallout4/mods/110353) | Optional but recommended |
| [FO3 - Cube Experimental](https://www.nexusmods.com/fallout3/mods/6270?tab=description) | Optional but recommended |
| [FO3 - Custom Vector maps](https://www.nexusmods.com/fallout3/mods/566?tab=files) | Optional but recommended (Monochrome version) |
| [FO4 - Upscaling Custom](https://www.nexusmods.com/fallout4/mods/108772) | Optional but recommended |

## Converter Details

The converter tries to copy as much from fo3 and nv into fo4 as possible. Some items are the fo4 version though. So in the FO3/NV worldspaces, it can vary:

- All outfits and armor are converted
- All unique items and weapons are converted, but shared items (stimpaks, globes) and shared weapons/ammo use fo4 version.
- All faces/bodies use the fo4 model/system, the converter tries to map the likeness as much as possible but people WILL look different than you're used to. [comparison1, comparison2]
- All unique creatures (centaur, gecko, companion dogs) are converted, but shared creatures (ghoul, molerat) use fo4 version.
- Terrain textures use fo4 version
- Karma is added and works in fo3/nv worldspaces
- All unique perks are converted, all shared perks use fo4 version. The level-up system is still fallout 4's - fo3/nv individual skills do exist but are derived/mapped from your other skills, skill books, and perks [see more here]
- You can have 1 humanoid companion plus all dog companions at one time.
- We also made a neat pip boy map plugin as part of this that draws the path to your destination like the original fo3 did through the metros etc [example [here](https://staticdelivery.nexusmods.com/mods/1151/images/110254/110254-1793396530-535760904.jpg)]
- We did a lot of work on lighting - the lighting systems are a bit different between the engines so we tried to make it look as true to the originals as possible but some creative decisions were made. Reactor ENB and the reactor preset fixes we have help with this too.
- Followers work from any game/worldpsace, and you can have one humanoid and 3 canine companions at once by default.
- Because it can be so different to start fo3 from an already leveled up fo4 character VS starting fo3 from a new chacter, we added some cross-worldspace difficulty settings in MCM. By default if you come to fo3 with a leveled up character from fo4 some things are too easy e.g. speech checks and disarming megaton etc. So those difficulty settings can those mappings "harder" / more balanced.

So some creative decisions were made, this is not an exact copy of fallout 3 but it's kind of a merge of the three games containing all worlds. It has a very different feel than the originals.

You can travel between the capital wasteland/commonwealth/desert at any time from a vertibird at red rocket. You can start a new game from any world, or you can use an existing fo4 save. there is a fo3->fo34 save converter tool in the installer too (that tool may be buggy if you have lots of mods in fo3 though).

## Mods

You can add mods to your fo3/nv base folders before converting and it will convert anything in there - however this is highly experimental and more testing is needed. (For example we are requiring ATMOS fo3 interior lighting overhaul as part of the installation which just means installing it into your fallout 3 folder before converting). Many FO4 mods and enbs are also compatible, but additional testing is needed. It is highly recommended that you get Fallout 34 working with only it's requirements first, then add on things after.

Compatible with [this upscaler plugin](https://www.nexusmods.com/fallout4/mods/108772) which i have contributed some code to, and can recommend.

## Testing & State

We have tested a lot and tried to make sure the main story and major sidequests are working properly, in all fo4 game versions. We tested multiple different story paths good karma / bad karma etc. We have not tested every side quest yet or every choice path so there will be some bugs somewhere. Updates & bugfixes will be done as an additional esp/fose mod copied on top of what the installer does, so you hopefully won't have to re-run the installer to get updates.

FO3:

- Main game, main story, side missions: yes
- DLCs: Broken steel, the pitt, mothership zeta are yes, operation anchorage and point lookout are no.

FNV:

- Main game, main story, side missions: yes
- DLCs: Honest Hearts (zion) yes, others are no.

We could use help from the community in testing and reporting bugs - we will work on fixing them.

It is compatible with All versions of Fallout 4: OG, NG, AE. It's a lot to test all parts of the game in all versions, but so far it seems to work similarly in all of them. We did the most testing in NG. All testing was done withOUT the "high resolution textures fo4 dlc"

Testing was mostly done using all "optional but recommended" mods in the mod requirements, so it is recommended to have those too.

Report bugs so we can fix them! Make sure to attach installer log fose log and buffout crash log, and tell us which game version you're on.

Helpful commands in case of bugs or when testing:  
"tcl" can toggle collision and help you get out if you get stuck anywhere.  
"enableplayercontrols" can help you if you can't move when you're supposed to.  
"enablefasttravel" ( cqf F34_CoreQuest "F34:Core.FreeFastTravel" "console" )

## Multiplayer & Online

Check out Fallout 34 Online too - an online mod for Fallout 34 that brings coop and PvE style events to your game. You can also see other people playing just by having the mod installed. Works with all worldspaces - FO3/NV/FO4. [[see more here]](https://www.nexusmods.com/fallout4/mods/110353)

## Updates

Some things we will still be providing updates on:

- FO3/FNV weather/atmosphere/tinting matching the original game better.
- Bugfixes
- All DLC supported
- Workshop settlements in fo3/nv worldspaces / cross-worldpsace quests.

[Join my modding discord here](https://discord.com/invite/hQAMQbH3MQ)

Fallout 3 is my favorite game. Fallout 4 is my favorite game engine.

## Other

This mod is completely separate from [the capital wasteland project](https://capitalwasteland.com/). That project is more ambitious and aims to remake many elements for a higher quality experience. This project aims to create a fallout 3 and NV experience inside of fallout 4 by conversion / without creating new assets manually.

See credits.

## Politics Reference

This mod is "AI-Assisted". This project is not "vibecoded". An incredible amount of manual work and over 15 years of fallout modding expertise was put into this project. AI was involved too but likely not in the ways you'd expect. this is a handcrafted mod at the end of the day, and a lot of manual work went into it.

There is a way to contact us privately in the discord if you ever need to.

## Installation

1) Copy in all requirements into your fallout 3, fallout NV and fallout 4 installs (and add to plugins.txt or use mod manager). Review all requirements carefully.
2) Run Fallout 34 installer (takes ~2 hours to convert everything) (have it be the only thing running)
   - The installer can take as little as 2 hours on a good computer and 3-4 hours on an older computer with less ram.
3) Copy in the separate Fallout 34 bugfixing patch into Fallout 4 after the installer (none may exist yet)
4) You can either load an existing Fallout 4 save, go to red rocket near sanctuary, fast travel to capital wasteland or mojave, begin your playthrough there - or you can start a new game and it will prompt you for which location to start from. Either way Fast travel back to the Commonwealth from virtibird anytime
5) in-game fixes:
   - MCM -> FallUI - Inventory -> Interface Coloring -> Pipboy  = "Green"
   - MCM -> Fallout 34 -> Gameplay -> Map background opacity = adjust accordingly. Depending on the mods you have installed, this needs to be either 50% or 100% for the map to be not-too-bright or not-too-dim.
   - uGridsToLoad=7 is recommended for a nicer visual experience if you have a higher-end pc but can strain performance otherwise
   - If you have any issues, try "low/medium" graphics preset on fo4 first and get that working. i've tried the 'ultra' preset on a middle-pc and got crashes, so for the ultra preset to work you need a higher-end pc. But otherwise in general you should get roughly fo4 performance.

## Note from Mod Author

There were A LOT of bugs that we fixed. We had to do dozens of full playthroughs of each game, including of the dlcs we support. We would fix a bug only to learn it affected something else in another area etc.

That being said because of the work we did the main story and bigger sidequests and supported dlc all seem to actually work well! So we feel comfortable releasing this.

That also being said.. we cannot test every path there are so many to test. We've tested good karma playthroughs, bad karma playthroughts, speech options etc but we have not tested every single possible path, and so there will be some bugs in some paths somewhere. please report them! we will continue working on this and will fix them!

This is a big passion project and my hope is to become a bigger part of the fallout modding scene as i am very passionate about it. i am looking to connect with other modders and collaborate.

We are building on a lot of peoples work, we are making sure to credit them below, and also to respect the license for each thing we're using. It would not be possible without them!

Please join our discord here [https://discord.com/invite/hQAMQbH3MQ](https://discord.com/invite/hQAMQbH3MQ) there is a button to contact me directly/privately or you can use public channels come and discuss modding!

## Credits & Legal & Source

We do not ship ANY game files as part of this. Zero! This is just a standalone converter that will convert your local fallout 3 and nv files into your local fallout 4 files. You must own and install both games yourself for this to work, and then run the installer to convert everything on your local machine. This is the only way we can distribute the mod legally.

We want to open source this converter code fully eventually if we can but we just need to better understand the legalities around that, and we want the code to be in a better place before we do too.

There are some parts of this code that MUST be open source, and so here they are:  
https://github.com/cobaltmods/fallout34havok  
This is an open-source GPL tool that the installer uses to convert game files etc.

CREDITS:

**Fallout 34**
- Cobalt - original mod creator, the converter, installer, testing, Fallout34.dll (F4SE plugin), bugfixing, creative direction
- [Becibis](https://www.nexusmods.com/profile/Becibis) - Community patches (such as sprint fix, other), community & moderation, testing
- Link - Community patches (such as armor stats fix, patrols, other), testing
- There are now many other community members helping us fix, test, and discuss how to move this mod forward. If we have forgotten your name here please let us know.

**Bethesda Game Studios** - Fallout 3, Fallout: New Vegas (Obsidian Entertainment) and Fallout 4. This mod contains NO files from Fallout 3 or New Vegas: the installer converts *your own* copies on your PC. You must own all three games. Fallout 34 is not made, supported or endorsed by Bethesda Softworks or ZeniMax Media. Fallout is a trademark of ZeniMax Media Inc.

**Required mods (you must install these yourself - please endorse their authors):**

- [F4SE - Fallout 4 Script Extender](https://f4se.silverlock.org/)
- [Address Library for F4SE Plugins](https://www.nexusmods.com/fallout4/mods/47327)
- [Buffout 4 NG](https://www.nexusmods.com/fallout4/mods/64880)
- [Extended Dialogue Interface (XDI)](https://www.nexusmods.com/fallout4/mods/27216)
- [High FPS Physics Fix](https://www.nexusmods.com/fallout4/mods/44798)
- [LevelUpMenuEx](https://www.nexusmods.com/fallout4/mods/28822)
- [Mod Configuration Menu (MCM)](https://www.nexusmods.com/fallout4/mods/21497)
- [FallUI - Inventory](https://www.nexusmods.com/fallout4/mods/48758)
- [The D.C. Interiors Project](https://www.nexusmods.com/fallout3/mods/5573)
- [ATMOS - Interior Lighting Overhaul](https://www.nexusmods.com/fallout3/mods/25911)
- [Fallout Street Lights](https://www.nexusmods.com/fallout3/mods/8069)

**Optional but recommended mods (you can install these yourself - please endorse their authors):**

- [REACTOR - A Fallout 4 ENB](https://www.nexusmods.com/fallout4/mods/57321)
- [ENBSeries](http://enbdev.com/)

**Converter software included and used (licence texts in the download's LICENSES folder):**

- [PyNifly](https://github.com/BadDogSkyrim/PyNifly) by BadDogSkyrim - Havok collision and FO4 animation code (GPL-3.0, shipped as a separate open-source tool, source: https://github.com/cobaltmods/fallout34havok), building on [nifly](https://github.com/ousnius/nifly) by ousnius and [HavokLib](https://github.com/PredatorCZ/HavokLib) by PredatorCZ
- [DirectXTex / texconv](https://github.com/microsoft/DirectXTex) - Microsoft (MIT)
- [FFmpeg](https://ffmpeg.org/) - the FFmpeg developers (LGPL-2.1+, build by BtbN)
- [Python](https://www.python.org/) - Python Software Foundation (PSF-2.0), with Tcl/Tk (BSD-style)
- [NumPy](https://numpy.org/) (BSD-3-Clause; bundles OpenBLAS, LAPACK) and [Pillow](https://python-pillow.org/) (MIT-CMU)
- [Nuitka](https://nuitka.net/) - Kay Hayen (compiler; runtime under the Nuitka Runtime Library Exception)

We are only able to use that software in the distributed converter because it is either open source or it is GPL-3 and we have included the source as GPL-3 above as well.

THIS ALL WOULD NOT BE POSSIBLE WITHOUT ALL OF THESE TOOLS AND AUTHORS MENTIONED ABOVE CREDIT GOES TO THEM.
