## Updates

True Ultima V rivers and edges have been created. Very hacky/tricky under Unciv limitations, but overall accomplished! This completes the purge of all hex-based graphics. Demo images to come of the new edges. Minor precision tweaks to follow.

# UltimaV-tileset
Retro tileset graphics mod for the Ultima V map [Britannia](https://github.com/hackedpassword/Nextgen-Maps#britannia-overworld), and a component of the (wip) U5 mod.

## Features

- All square tile graphics, concealing the underlying hex grid
- Movement and reachabilites remain hex which actually feels like an improvement on original gameplay - hex underpinnings are mandatory being built on top of Unciv
- Original tiles and sprites ripped from sprite sheets, thank you sprite rippers!
- None or minimal sprite alterations sans effects like submerged units or moongate glows, 
- 1:4 scale Britannia map (128^2) is vast and expansive despite one-quarter scale pushing Unciv to the razor-edge of memory limitations
- Terrain sprites use a 2-pixel alpha edge trim for blending since the hex grid is notoriously imprecise for hard clean tiling - you get more lush environment as a result
- Terrain feature sprites leverage the alpha channel to layer the graphics into the expected appearance while retaining gameplay behavior, like cutting down forest or jungle (dense forest)
- Treasures hidden throughout the world, inclusive of reagents
- Exploration "feel" *closely* retained - line of sight mechanics duplicate the wonder of adventure
- Water terrain given special attention for representative accuracy since naval travel was a core mechanic
- Re-themed improvements and resources
- Custom [Shadowlord realm themed borders](https://github.com/hackedpassword/Ethereal-borders) look like wild energy barriers (probably the coolest Unciv edge mod to date!)
- Towns, shrines, abbeys, etc, all present - even Moongates, will eventually migrate to becoming named Wonders and City-State Nations
- Road improvement pre-placed on paths
- Carefully hand-placed resources across the land ensuring an amazingly balanced game as civs scale, from start to end
- Meaningful economics and trading - a common luxury item to you may be highly sought by a distant civ, while a rare item could draw unwanted attention
- Sprites are layered specifically to partially conceal items that are best discovered by explorers, or for logical layeribg appeal (Forest overlays Fort for example) - look closely you probably missed a hidden item! (which is satisfyingly rewarding when found)
- Great people, civilians, and all major endgame units re-themed
- Intense attention to crafting the map as accurately as possible factoring technical design challenges

## Not present, yet
- Lots of other re-themed units (however the total Ultima V creature/human count is pretty low so this will require special attention)
- Re-themed nations to become pre-placed towns (say like Paws or Moonglow, etc)
- Translation names of game assets from Unciv base to Ultima names, see [Ultima V base](https://github.com/hackedpassword/UltimaV-base/blob/main/jsons/translations/English.properties)
- Re-themed icons
- Other things that bring that authentic Avatar feel home and onto the battleground
- Granting promotions that act like items, example: climbing gear promotion for impassable terrain (mod Z2/Zelda 2 makes extensive use of this mechanic)
- Better use of wonders to reflect location attributes

## How do I get this because it sounds awesome!
1. Download Unciv
2. Within Unciv, in the Mods menu download `Ultima tileset` mod, `Ethereal borders` mod, and [Nextgen Maps](https://github.com/hackedpassword/Nextgen-Maps) mod
3. In the New Game screen choose "Custom map", look for Britannia, select
4. Make sure `Ultima tileset` and `Ethereal borders` are selected mods
5. Add some civs and nations, I think 12 civs and 20 nations should provide plenty of unrushed exploration and foundation

## What does it look like?

With the new rivers and edges, these images need to be updated, but you get the idea at a glance.

![](https://github.com/hackedpassword/Unciv-Assets/blob/main/Images/Ultima%20V/u5_next_phase.png)

You see the new edge tiles improve square tile immersion. This needs more work but it'll do for now!

![](https://github.com/hackedpassword/Unciv-Assets/blob/main/Images/Ultima%20V/u5_next_phase2.png)

Rivers true to their graphical Ultima roots flow across the land.

![](https://github.com/hackedpassword/Unciv-Assets/blob/main/Images/Ultima%20V/new_rivers.png)

Scenes like this deserve an award.

![](https://raw.githubusercontent.com/hackedpassword/Unciv-Assets/refs/heads/main/Images/Ultima%20V/Award%20winning%20screenshot.png)

For a comparison, here's the original graphics:
![](https://github.com/hackedpassword/Unciv-Assets/blob/main/Images/Ultima%20V/original_map-at-cove.png)
I love this map! Credit to the author @drrak. The whole map is [here](https://drrak.github.io/ultima5/).

What should stand out the most is that you don't see hex tiles, only "square" tiles. This is an intended and tricky effect to mimic the original looks of the 1988 game.

There's a slight intermix of sprite tilesets, mostly PC version. I wanted to use the Apple ][e version but those sprites are far too low quality so I believe the PC version is my goto.

This mod could use a star :star: to show support of the unique retro concept!
