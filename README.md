## Overview
Mad Mannequins is a sizeable part mod that adds a considerable number of human-anatomy-themed parts, which are used to build the namesake Mannequins. At present, the mod contains a total of 214 parts in total.

## Features
The mod features 4 distinct mannequins, from which the individual parts have been harvested. All pats are stackable without the need of the Stacker mod. These include:

1. A traditional wooden-style drawing mannequin. Androgynous, which is to say ambiguously-gendered, the mannequin is simple, subdivided into the major body parts, perfect for creating low-rendering-cost figures.
2. A Female human mannequin, designed in line with average-ideal body proportions for the given age range in mind. This mannequin requires considerably more resources to paint, but has been designed in such a way as to optimise the painted textures. 
3. A Male human mannequin, designed in line with average-ideal body proportions for the given age range in mind. This mannequin requires considerably more resources to paint, but has been designed in such a way as to optimise the painted textures. 
4. A largely accurate human Skeleton, divided into several major bone groups. As with the previous two mannequins, coloured bones require considerably more resources to paint. 
5. A largely accurate Paint horse, with several smaller parts making up the head, though lacking a tail.

This mod is still in development, and will receive irregular, but large updates. When making suggestions, please note that the theme of this mod is realistic anatomy, and suggestions that do not fit that theme will likely be ignored. There are also likely to be some bugs to fix, so please make certain to give detailed accounts and report of them.

This mod must be installed via the Spore ModAPI Easy Installer, available as part of the Spore ModAPI Launcher Kit, available here: http://davoonline.com/sporemodder/rob55rod/ModAPI/Public/.

## Known Issues
When reporting issues, please be as specific with your information as possible:
* Indicate what distribution of the game you are running: Steam, EA App, GoG, Disc, etc., each of these may have relevant issues to consider.
* Beware the "I am All" falacy: what happens to you does not necessarily mean it happens to everybody, there may well be something wrong with your specific setup.
* Correlation vs Causation: a mod observed to be causing issues may not be the direct cause of a crash or given problem, rather it may just be triggering some other greater problem.

### Increased likelyhood of crashes
After repeated failures to replicate reported crashes, it can be assumed that such crashes are either rare, misattributed or are symptoms of a deeper problem. A few suggestions:
* Be sparing with the number of parts used, as their model complexity is generally higher than what Spore expects.
* In the case of many mods being installed at once, there may be unexpected conflicts. Overloading the game with dozens of mods is ill-advised.
* Certain hardware may struggle to keep up with Spore's demands in general, even years later.
* Install the [4GB Patch](https://ntcore.com/4gb-patch/) from NTCore (not applicable to Steam distributions of the game after October 2024, inquire at the Spore Modding Community Discord Server.)

### Low resolution textures on paintable parts
This is unfortunately a side effect of the system by which Spore generates its textures. Model textures are not created independently, but are sectors of one unified texture set for the entire Creature, which is then compressed. The HD Graphics Fix can help by increasing the maximum size this texture can be, but abusing the number of paintable parts will still cause final painting quality to dip with each one added. This is not currently fixable.

## Change Log

#### 160420221851 (GitHub Release)
- Uploaded mod to GitHub due to issues with Google Drive.
- All parts now unlock at the start of Creature Stage.
- Added Stacking component, accessible when installing the mod and then again after installation through the Easy Mod Uninstaller's settings menu.

#### 020920211406 (New Release) - Massive Overhaul:
- Remade all Human mannequin models to consist of more parts for greater flexibility. Mannequins made with older versions will be left unnafected. Parts from older versions will still be usable, but not available via the palette.
- Removed variants of heads, will be re-added to as variants for new parts later.
- Fixed issue with skeleton scapular having inverted normals.
- Updated icons for all parts.
- Added Horse mannequin and associated parts.
- Repaired textures on several parts, fixing shading errors.
- Updated stacking mechanics to include Outfitter parts and Dark Injection parts, stacking modifier option pending.
- Mod is now distributed in compressed .sporemod format to save on space and download times, requiring use of ModAPI Easy Installer.
#### 051020192251 - Fixed an error where the Humerus Bone was causing creations to be unsaveable.
#### 051020191632 (Post-release) - Fixed a texture error on the Joint part, and fixed symmetrical variants from stopping creations from saving.
