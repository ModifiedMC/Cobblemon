# Modified Cobblemon Essentials - Master Changelog

**Join the Discord:**
https://discord.gg/tdMWUuwFKB

**Support the Modpack:**
https://ko-fi.com/modifiedmc

**Need a Server?**
https://bloom.modifiedmc.com

---

Jump to a Version: 
- [[v1.3.0]](https://github.com/ModifiedMC/Cobblemon/edit/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v130)
- [[v1.2.0]](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v120), [[v1.2.1]](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v121), [[v1.2.2]](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v122), [[v1.2.7]](https://github.com/ModifiedMC/Cobblemon/edit/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v127)
- [[v1.1.2]](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v112), [[v1.1.1]](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v111), [[v1.1.0]](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v110)
- [[v1.0.2]](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v102), [[v1.0.1]](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v101), [[v1.0.0]](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#v100)

---
# [1.7.1]
- Fixed network protocol disconnect on servers, added missing mods, removed mods supposed to be taken out last update
- See more important updates / notes to server owners below!
 
---
# [1.7.0]
### NEOFORGE VERSION IS NOW 21.1.211
- New seasonal field research quests have been added! (20 new quests, the next field research will be added in roughly 4-5 weeks!)
- Many mods were updated this release, fixing many longstanding bugs in mods such as; Accessories, Artifacts, KubeJS, Tectonic, Create Addons, as well as updates to many of our cobblemon addons; Raid Dens, Fight or Flight, Unchained, & more!
 - Several QOL Updates, Fixed issues with serverpack/variables.txt, New leadboard system to track/compare stats with friends, Enabled Silktouch dropping spawners, More info in JEI for loot tables, Better Biome Block Blending, Significant Performance Improvements, etc
  - Introduced a new [Spawn Chaining](https://www.curseforge.com/minecraft/mc-mods/cobblemon-spawn-chaining) mechanic, where the actual rate of spawns increases when chaining mons. The other shiny, nature, & other stat bonuses still apply for their respective KO / catch streak or totals.
  - Increased worldgen performance by ~30% (tectonic), removal of borked structures, optimized rendering of entities & graphics through flywheel, networking fixes, and reduced hud updates - drastically improving performance overall in many aspects of the modpack.
  - Updated cobbreeding to use the Masuda Methood again -  If the two pokemon making an egg belong to different trainers, the shiny rate will be multiplied significantly (odds are roughly 1/2700 instead of 1/8192)
### NOTICE TO SERVER OWNERS:
  - Even though there were structures mods removed, **a new world is not necessary** but recommended - moogs structures will stay since they use vanilla blocks, but the VS blocks will be converted to air, I have hopefully removed all logspam associated to this change and it is safe to update from previous versions.
  - Changed some settings on Server Core optimizing many areas of spawning, and also allowing for more total hostiles improving mob farms but server owners please note you may need to tone this back depending on your total number of active players

### ADDED MODS
- [Leaderboards](https://www.curseforge.com/minecraft/mc-mods/leaderboards)
- [Vanillin](https://www.curseforge.com/minecraft/mc-mods/vanillin)
- [Colorwheel](https://www.curseforge.com/minecraft/mc-mods/colorwheel)
- [Krypton FNP](https://www.curseforge.com/minecraft/mc-mods/krypton-fnp)
- [Spawn Chaining](https://www.curseforge.com/minecraft/mc-mods/cobblemon-spawn-chaining)
- [Advanced Loot Info](https://www.curseforge.com/minecraft/mc-mods/advanced-loot-info)
- [Better Biome Reblend](https://www.curseforge.com/minecraft/mc-mods/bbrb)
- [LambDynamicLights](https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights)
  
### REMOVED MODS
- Sodium Dynamic Lights, Immersive Lanterns (replaced)
- Valhesia Structure series - see note at bottom of this updates changes for more details
- Moogs structure series - causing world gen issues, and taking up valuable structure placement from better structures in the modpacks, thanks for your community feedback !

---
# [1.6.2]
- Fixed client / server mod list sync
- Fixed enchanted book / redstone dupe - thanks @exbubba for providing the scripts
  
---
# [1.6.1]
- Fixed custom recipes not applying as intended
- Improved performance / unecessary extra ticking events
- Resolved server freezing during RTP or Dimension switch
- Fixed issues with modded enchants displaying properly on items
- Fixed issues with fossil quests not tracking after mon is registered
- Updated resource packs; Cobblemon Interface + RCT Trainers Textures
- Updated several mods - many fixes for create addons, Oritech, raid dens, & more!
- Changed all starter mon to level 5, added two new "Regions" adding 6 new starters!
- - "Tokiwa"; Abra, Mankey, Sandile | "Koryū"; Axew, Horsea, Trapinch
- Optimized Cobblemon Config stabilizing TPS drops during spawn events & on servers with many Pasture/Egg farms.
- Slightly changed cobblemon rarity config, each time a spawn event fires it has a 90% chance to be common, 8% uncommon, 1.5% rare, 0.5% ultra-rare
- - (previous rates were; 94.3%, 5%, 0.5%, 0.2%)


### ADDED MODS
- [Create: Smart Bounds](https://www.curseforge.com/minecraft/mc-mods/create-smart-bounds)
- [Toggleable Enchants](https://www.curseforge.com/minecraft/mc-mods/toggleable-enchantments)
- - "J" by default to toggle your enchantments!
- [Building Wands](https://www.curseforge.com/minecraft/mc-mods/building-wands)
  
### REMOVED MODS
- Toggle Enchantments (replaced)
- Spark
  
---

# [1.6.0]
### NEOFORGE VERSION IS NOW 21.1.209
- Fixes many bugs with recent versions of the modpacks, performance improvements, & Project files are now Synced with GH Again, thanks to all reports / suggestions in discord!
- There will be a quest overhaul coming soon to fix up old quests, add new quests based on newly added content, and add NEW seasonal quests!

#

- Updated default server variables.txt, removed problematic java arg, updated neoforge version.
- Resolved more Memory Leaks, Optimizations for mods like Refined Storage, JEI, & more!
- Significantly cleaned up the configs, removing many outdated files.
- Updated Datapacks. AllTheMons x MegaShowdown new update (by Lvnatic)
- Swapped EMI/TMRV for only JEI, expect longer initial client load times but should resolve many issues with the previous EMI setup.
- Fixed issues with players accessing the Aether Accessories items / GUI, enabled the specific gui button & resolved overlapping buttons.
- Fixed issues with the CobblemonUtil Items (Caps, Feathers, Shiny Cards, Etc.) - restore previously aquired items as well as fixes the quest shop.
- Fixed several issues with quests - resolved missing textures, updated chapter icons, updated several quests, added rewards, removed depreacted mod quests.
- Merged Mort's Fixes for the build script to all Modified Cobblemon Repos, allowing for full development with VSC/WSL again!


### ADDED MODS
- [Cobblemon Raid Dens](https://www.curseforge.com/minecraft/mc-mods/cobblemonraiddens)
- [Cobblemon Player Exp](https://www.curseforge.com/minecraft/mc-mods/cobblemon-playerxp)
- [JEI](https://www.curseforge.com/minecraft/mc-mods/jei)
- [JEResources](https://www.curseforge.com/minecraft/mc-mods/just-enough-resources-jer)
- [JEProfessions](https://www.curseforge.com/minecraft/mc-mods/just-enough-professions-jep)
- [Refined Storage x JEI Integration](https://www.curseforge.com/minecraft/mc-mods/refined-storage-jei-integration)
- [Chroma Carvings](https://www.curseforge.com/minecraft/mc-mods/chroma-carvings)
- [Create: Railways Navigator](https://www.curseforge.com/minecraft/mc-mods/create-railways-navigator)
- [Merge Enchantmants](https://www.curseforge.com/minecraft/mc-mods/merge-enchantments)
- [Toggle Enchantments](https://www.curseforge.com/minecraft/mc-mods/toggle-enchantments)
- [Hostile Neural Network](https://www.curseforge.com/minecraft/mc-mods/hostile-neural-networks)

### REMOVED MODS
- EMI & Addons (Loot, Enchanting, Ores, Professions, Extra Mod Integrations)
- Refined Storage Emi Compat
- Cardiac, EasyMobFarm, Ultimine Addition (Causing Significant server lag, issues with performance)
- Showcase Item, RCTH (Redundant)
- Chat Toggle
---

# [1.5.5]
- Fixed Villagers having white eyes
- Rolled back Lightmans Currency Version.
- Fixed shader menu & other gui screens from being unavailable due to background blur

---
# [1.5.4]
### NEOFORGE VERSION IS NOW 21.1.208
- Fixed not being able to create a new world, and many other crucial pack fixes.
  
- Fixed issues with mods interupting world saving.
- Fixed Accessories crashes, invalid item tag, etc
- Removed EMF / ETF & Fresh Animations resourcepack
- Drastically improved F3 menu by hiding most info panels.
- Dimension Dungeons; fixes longstanding bug with patchouli guidebook!
- General Bug Fixes, Mod Updates; Little Tiles, SimpleVoiceChat, & many more!
- Memory Leak is now resolved with Refined Storage, there should be much better server performance now!
- Swapped Journey Map for Xaeros Minimamp, Worldmap, & XaeroPlus - Should drastically improve server performance but there are a few mods that dont have as good of integration with Xaeros vs JM.
- The map entity icons were set with GUI scale of 3x, so if you run anything else you may need to adjust. (ESC > Mods > Xaeros Mini > Entity Overlay Settings > Set Icon Scale)
- CLAIMING: still handeled through FTBChunks so no changes required on that end for the server/players needing to update claims. To access this claim map you now click the map icon in the top left when you open your inventory. The Xaeros WorldMap is bound to M by default (not for claims, shows icons, waypoints, etc)
  
### Translation
- Add **PT_BR** localization by _PrincessStellar_

### Added mods:
- Custom Regions Unexplored fix (Yellow571)
- Tool Belt
- Xaeros Minimap
- Xaeros Worldmap
- XaeroPlus

### Removed Mods:
- AllTheOres / AllTheCompat
- Paper Doll
- Journey Map
- Journey Map Integration
- EMF / ETF / Fresh Animations RP
- Wither Spawn Animation

---

# [1.5.2]
- Resolved incorrect command to spawn the last trainer of BDSP, you can now summon Cynthia through quests.
- Lots of Fixes for side tagging, removing several client side mods from server packs. (TY @Laya_Reed for the list of mods)
- Fixes for several crashes, including network packet issues, more memory leak fixes, etc
- Fixes for Accessories Menu Error, and many other Crashes with mods like Sophisticated Storage/Backpacks
- Improved Render performance with shaders enabled (Flerovium)
- Tons of fixes for Simple Voice Chat ([see most of the changes here](https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat/files/6951851))
- Create Addons such as Central Kitchen now has alot more mod compat! Adding Support for many other Farmers Delight Addons!
- Many other Fixes to Create Addons, fixed invalid items/liquid, console/log spam, server crashes, etc

---
# [1.5.1]
- Fixed crash on new world creation
- Fixed other server & client crashes

---
# [1.5.0]
- Resolved Various Memory leaks, Client & Server crashes.
- Little Tiles is back! Mod performance seems much better after testing recent versions.
- Unified drop for Create: Zinc, no more ATM Zinc from ores resolving many recipes from sidemods.
- Crucial Updates to tons of mods! Aether, Artifacts, Cataclsym, Fight or Flight, Refined Storage, etc, etc.

### ADDED MODS
- [Curios](https://www.curseforge.com/minecraft/mc-mods/curios)
- [Little Tiles](https://www.curseforge.com/minecraft/mc-mods/littletiles)
- [Accessories Compat Layer](https://www.curseforge.com/minecraft/mc-mods/accessories-compat-layer)

### REMOVED MODS
- [EmoteCraft ](https://www.curseforge.com/minecraft/mc-mods/emotecraft-forge) (causing issues)
- [CC Compat layer for Accessories](https://www.curseforge.com/minecraft/mc-mods/accessories-cc-layer) (replaced)
  
---
# [v1.4.0]
- Removed most AllTheOres from spawning
- Fix issues with dedicated servers crashing
- More updates for refined storage fixing many critical bugs, dupe exploits, etc.
- Block cards dropping from cobblemon / trainers, please remove any of these dropped cards if you have them from previous updates as they spawn pokemon that bug out the pc.
- Notice: Grave mod was replaced so be sure to collect items from pending graves BEFORE updating

### ADDED MODS
- Gravestone
- Gravestone Curios Compat

### REMOVED MODS
- Youre in Grave Danger (replaced)


---

# [v1.3.2]
### NEOFORGE VERSION IS NOW 21.1.200
- Some more fixes for refined storage, removed raised, fixes for serverpack, and added some missing mods from other modified cobblemon modpacks.  

### ADDED MODS
- [Storage No Poof](https://www.curseforge.com/minecraft/mc-mods/storage-no-poof)
- [Metal Barrels](https://www.curseforge.com/minecraft/mc-mods/metal-barrels)
- [OpenBlocks Elevators](https://www.curseforge.com/minecraft/mc-mods/openblocks-elevator)
- [Wither Spawn Animation](https://www.curseforge.com/minecraft/mc-mods/wither-spawn-animation)

### REMOVED MODS
- Raised
 

---
# [v1.3.1]
- Fixes for quest lang, crash on server startup, and added Immersive Paintings mod.
- Just a small hotfix, read more important updates below!
ADDED: [Immersive Paintings](https://www.curseforge.com/minecraft/mc-mods/immersive-paintings)
---

# [v1.3.0]
- This update should be much more stable then 1.2.x builds, Many large mods got some much needed updates.
- Important change to FTB Teams - but this will stop your friends from  resetting your Trainer Levels finally!
- First translation for quests is now available, (ES_ES) if you want to translate for your language, or to contribute anything else, make a pull request on Github! All modpacks are now finally synced with GH again, or you can make a ticket in discord! ([Join here](https://discord.gg/k4jWHxy2M9))

### NEOFORGE VERSION IS NOW 21.1.199
Summary of bug fixes:
- Fixes to Raised / icon alignment
- Almost Unified made several optimizations and improved load times
- Fixed a few crashes in both singleplayer and isolated dedicated server issues
- Lots of crucial mod updates - Refined Storage, Patchouli, TMRV (JEI), & many more!
- Fixed issues with certain quests displaying null textures, updated some descriptions.

## NEW FEATURES
- Cobblemon Challenge now has support for multibattles!
  -- /challenge <username> level <level>
- Added Spanish Translation to quests - thanks to @KarritoQchao on discord!

## IMPORTANT UPDATE TO TEAMS / NOTE FOR SERVER OWNERS:
- Updated FTBTeams to not allow you to invite or join other players to your team to avoid progress getting reset or sped up unintentionally from other players. You can still "Ally" other teams to allow other players access to your claims.
- Also added a few default FTBRanks for server owners, default is now 'trainer' - 200 claims / 0 forceloaded, 'VIP' - 500 claims / 1 forceload, And some default staff roles - Helper, Mod, Admin with some useful commands. If server owners want to add more commands to any of the ranks, go into the WORLD > ServerConfig > FTBRanks > and you can see a list of all available commands in the README.txt, copy the desired command you can set it to ':true' (or false to remove access).
- Please be sure to back up your worlds as some mods like Little Tiles had to be removed, safe to update but to get rid of the log spam if for example little tiles blocks were in your builds, use log be gone. Config > logbegone.json


## ADDED MODS
- [Create: Copycats+](https://www.curseforge.com/minecraft/mc-mods/copycats)
- [Create: Slice and Dice](https://www.curseforge.com/minecraft/mc-mods/slice-and-dice)


## REMOVED MODS
- Connectivity
- Structurify
- Soul Fire'd
- Little Tiles
- AetherAddon: Protect your Moa

---

# [v1.2.7]
Tons of mod updates, fixes to resource loading, and other general modpack improvements
### NEOFORGE VERSION IS NOW 21.1.197

MoreCobblemonTweaks has finally been updated to recent versions of cobblemon again!
There is now better tooltips on the Eggs from Cobbreeding, AND tons of PC Enhancements - Show IV/Stats directly in the PC, search and rename your boxes, multiselect to move/release, plus background customization!

Tons of updates to existing mods, and Added some more requested mods!

- **ADDED** Tool Belt - https://www.curseforge.com/minecraft/mc-mods/tool-belt
- **ADDED** Actually Harvest - https://www.curseforge.com/minecraft/mc-mods/actually-harvest
- **ADDED** MoreCobblemonTweaks - https://www.curseforge.com/minecraft/mc-mods/morecobblemontweaks
- **ADDED** KubeJS Tweaks - https://www.curseforge.com/minecraft/mc-mods/kubejs-tweaks



---
 
# [v1.2.6]
Lots of fixes, mod updates, & new items!
### NEOFORGE VERSION IS NOW 21.1.191

* Performance improvements, fixes to several crashes, & more!
* Fixed many scripts, cleaned up code and added some debug logging
* Updates to several large mods, ie. Mega Showdown huge update/rework, many, many fixes!
* Fixed more issues with items being hidden from EMI / JEI, also items missing from loottables.
* Changed journeymap cobblemon icons to [Maxis Pack](https://www.curseforge.com/minecraft/texture-packs/journeymap-cobblemon-icons) - fixed issues with some mons not displaying an icon & not being enabled properly. Recomended scaling is around x1.35


---
# [v1.2.3-5]
Archived for bugs / crashing.

---
# [v1.2.2]
More fixes, Villagers now follow you if you're holding an emerald block!
### NEOFORGE VERSION IS NOW 21.1.186

* Removed all client side mods from the serverpacks. Apologies for the delay on this hotfix!
* Fixed some issues with EMI/JEI not loading recipes properly, fixed some mod compatibilty.
* Villagers will now follow you if you're holding a Emerald Block, Similar to how animals follow with wheat/carrots/etc.
* **CarryOn now blocks ALL entities except for Chests, Furnaces, & Spawners** as too many mob entities were causing issues. More blocks/tile entities may be added in the near future. Be sure to suggest some in the [Feedback section of the discord](https://discord.gg/WMWDbNgj7K) if you feel like I missed anything that should be moveable. **This also includes blocks like barrels, blast furnaces, & other modded chests like the sophisticated storage blocks*

---

# [v1.2.1]
- Crucial Bugfixes & Tweaks based on your feedback - [26-06-2025]
### NEOFORGE VERSION IS NOW 21.1.183

## Summary of Changes
* **Various Bug Fixes:** Fixed many issues relating to all the reported bugs (Death/grave issues, crashing, and other server disconnects)
* **More Ways to collect Em All!** - Breeding 2 dittos together now grants a random pokemon egg. (_Legendary/Mythical/UltraBeast/Paradox/etc excluded._)
* **More mob filtering options:** Torchmaster's Functionality to block cobblemon spawns replaced with **new Repel item** so Torchmaster now only works for hostile mobs.
* **EMI Compat added back to RS:** But be warned there are performance issues when displaying the tooltips for items in the RS system.
* **More Quest Updates!** Fixed a few broken quests, added Simply Swords Chapter & Rewards to various other chapters, and added even more quests further explaining some core cobblemon functions like the alternate forms, and other important items!
* **Tweaks for Mob spawn Limits** Fixed a few unintention blocks for certain hostile mobs, adding back functionality to vanilla spawners.
* **More ways to earn coins!** Several hostile mobs now properly drop Relic Coins as intended. Remember 10 relic coins = 1 Pokedollar, 100 Pokedollars = 1 Master Token!
* **More ways to convert currency:** Added several recipes so you can convert between the piles and blocks of pokedollars/mtokens

  
## ADDED MODS
- [Cobblemon Repel](https://www.curseforge.com/minecraft/mc-mods/cobblemon-max-repel) - Adds a few types of repels to block trainer and cobblemon spawns as needed.
- EMI RS Compat - Adds back the compat between EMI and Refined Storage 2
- [Scribble](https://www.curseforge.com/minecraft/mc-mods/scribble) - Book & Qwill QOL improvements
- [Simple Voice Chat](https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat)
- [Simply Swords](https://www.curseforge.com/minecraft/mc-mods/simply-swords) - Adds more varied weapons, currently only available as random quest loot from the "Mob Hunter" Tab. (**NOTE: **There is a known bug accessing your SS items from your Refined Storage Systems, please use alternative storage methods for these items.)

## REMOVED MODS
- Torchmaster Cobblemon Compat
- Nerunia (Ticking Entity Fixer)

---

# [v1.2.0]
-  Huge Balancing Changes & Complete Quest Overhual - [18-06-2025]
### NEOFORGE VERSION IS NOW 21.1.180

## Performance & Stability

* **Crash & Performance Fixes:** Addressed several underlying issues that were causing client crashes and poor pack performance for a more stable playing experience.
* **Tons of mods up to date:** Over 100 mods in the modpack received an update. Notable ones being Create with lots of bug fixes for its new systems, Tectonic with various worldgen improvements, & a ton of the cobbemon sidemods included in this pack.
* **Default Settings Adjustment:** To ensure a smoother initial experience for all players, Shaders and Distant Horizons are now **disabled by default**. Players are encouraged to enable and configure these in their settings menu. Distant Horizons settings are particularly hardware-dependent, so please tweak them carefully to match your system's capabilities (e.g., offloading to GPU or CPU).
* **Optimized Mob Spawning:** Overhauled the InControl mob limits for nearly every entity in the game. These new caps limit the number of non-essential mobs that can spawn per player, significantly improving performance and prioritizing the spawning of Cobblemon.

## Economy & Balancing

* **New Currency Streams:** With the massive influx of new quests, there are now more ways than ever to earn Pokedollars, rewarding both casual players and dedicated completionists.
* **Master Ball Rebalance:** To reflect the new economic balance and maintain their legendary status, Master Balls now have a trade-in value of **2500 Pokedollars**.
* **Gotta Catch Em All!"** So Dex completion is a posibilty, players can now store up to 1500 Pokemon, 50 pages total now!

## The Great Quest Overhaul!

This update introduces a **complete overhaul of the questing system**, with over **1000 new quests** designed to guide, challenge, and reward players of all types!

### Seasonal Field Research

* **Introducing Seasons:** A new, limited-time quest chapter has been added! "Seasonal Field Research" will feature unique challenges and rewards. We are currently planning for seasons to last approximately 6 weeks, but we welcome player feedback on the timing. Complete these objectives while you can!

* **Mod Tutorials & Guides:** Added comprehensive questlines that explain the core mechanics of almost every major mod in the pack, including:
    * **Cobblemon:** Completed all previous questlines and now covers advanced mechanics like Mega Evolution, Terastallizing, and Dynamaxing.
    * **Bosses & Mobs:** Learn how to tackle the dangerous new bosses and mobs from the Cataclysm mod.
    * **Farming & Cooking:** Guides for Farmer's Delight, Croptopia, and other food-related mods.
    * **Tech & Automation:** Tutorials for Create and all other major tech mods.
    * **Quality of Life:** Explanations for many of the helpful client-side and utility mods.
* **New Main Chapters:**
    * **Mob Hunter:** A new chapter for adventurers and completionists focused on tracking down and defeating various creatures.
    * **Loot Collector:** Test your gathering skills with this chapter dedicated to collecting rare and valuable items from across the worlds.
* **Dimensional Exploration Quests:** Embark on guided adventures with new questlines for every single dimension:
    * The Overworld
    * The Nether
    * The Aether
    * The End
    * The Deeper Dark
    * The Mining Dimension
    * The Dungeon Dimension

* **Quest Improvements:**
    * Fixed numerous issues with previously existing quests.
    * Enhanced quest clarity with more detailed descriptions, subtitles, and helpful information.
    * Added many more basic crafting quests to help new players get started and offer completionists more to do.



## Cobblemon & Mobs

* **Updated Mod Version:** The pack has been updated to the new MS x ATM version by Lvnatic, bringing a wealth of fixes, balance changes, and improvements.
* **Balanced Spawn Pools:** The Cobblemon spawn pools have been rebalanced for a more diverse and engaging world.
* **Expanded Ride List:** Added many more Pokémon to the list of rideable mounts.
* **New Mounting System:** You can now easily mount your Pokémon directly from the Cobblemon interaction wheel (Shift + Right-Click your lead Pokémon).
* **Spawn Notification Changes** - There is now a Journeymap waypoint shared to chat when certain tags of cobblemon spawn. (Legendaries, Mythical, Paradox, Ultra Beasts, Starters, & Shinies by default)
* **Texture Fixes:** Numerous texture issues have been resolved.



---

# [v1.1.2]
### Hotfix

   - Fixed Data Sync / registry error on join

 ---

# [v1.1.1]
### Expanding on the previous update

NEOFORGE VERSION IS NOW 1.21.172

## **⚙️ Core Changes & Fixes**
 - Worldgen improvements, chunks now generate quicker!
 - Significantly improved performance with Dyanmic Resources enabled again.
 - Fixed overlapping buttons in the Inventory GUI

 - Added some highly requested mods (Distant Horizons, Better Combat)

- Added new coin blocks and coin piles. 1 coin pile = 9 coins, 1 coin block = 4 coin piles.
   - Added New "Master Token" - Worth 100 Pokedollars, adjusted quests to reflect these changes
   - You can convert between relic < pokedollar < mtoken in the ATM & Store all coins in your wallet
   - Mobs Drop any of thier coins depending on rarity now, most mobs drop Relic Coins but it scales with difficulty
   - This only includes vanilla mobs for now, I will be adding all Cataclysm & Apotheosis Bosses to this coin drop system as well.

- More rideable mon fixes, fixed some mounts that couldnt fly
   - Even more rideable mon with more to come in future updates!
   - [Click here to see additions](https://github.com/ModifiedMC/Cobblemon_Overclocked/tree/main/kubejs/data/cobbleride/rideable_species)

- Added basic ender eye quests to better explain End Remastered.
- Added Candies to be purchased in the Modified Exchange (Both common & rare candies)
- More Quest revisions & Fixes - Lots more to come! Sorry for the wait in finishing out the questbook!

- Fixed ingame server browser ( You can now actually post your servers on -> https://minecraft.multiplayerservers.net/ )
     - servers can be shown on the site & in the pack's multiplayer menu!

## **➕ Added Mods**
- **[Distant Horizons](https://www.curseforge.com/minecraft/mc-mods/distant-horizons)**
- **[Create: Central Kitchen](https://www.curseforge.com/minecraft/mc-mods/create-central-kitchen)**
- **[Create: Integrated Farming](https://www.curseforge.com/minecraft/mc-mods/create-integrated-farming)**
- **[Create: Liquid Fuel](https://www.curseforge.com/minecraft/mc-mods/create-liquid-fuel)**
- **[Trade Cycling](https://www.curseforge.com/minecraft/mc-mods/trade-cycling)**

---

# [v1.1.0]
### Quest Additions & Crucial Pack Fixes!

## **⚙️ Core Changes & Fixes**

### **More Rideable Mons!**
- Raised overall base speed of all rideable mons
- Mainly extra legendary pokemon, but also a few easter eggs like Crobat & Bidoof!
- [Click here to see additions](https://github.com/ModifiedMC/Cobblemon_Plus/tree/main/kubejs/data/cobbleride/rideable_species)

### **Quest Updates!**
Quest Shop Updates & Lots more quests in the "Champions League" - Made it much more clear how to raise your level cap.
- More ways to earn PokeDollars!
- Added rewards on various chapters
- Permission / Unknown command fixes
- Added quests for all Gym Leaders / Key Trainers
- Added new "Sell" Section in the Modified Exchange
- Added a way to convert between coins in the Quests
- Added more items for sale in the Modified Exchange
- Added ability for player to run more commands via quests

### **NEW Unchained Update!** 
- unlock thresholds to multiply nearby spawns based on your current points for them. by default, ko streak of 5 gives x1.2, 10 gives 1.5x, 20 gives 2.0x, 30 gives 2.5x, 50 gives 3.0x, 75 gives 3.5x, and 100+ gives 4.0x

## **➕ Added Mods**
- **[Explorers Compass](https://www.curseforge.com/minecraft/mc-mods/explorers-compass)**

---

# [v1.0.2]
### more fixes

- added trainer quests to help more with progression map
- added fallingtree (tree feller for early game, there is still Ultimine)
- added darksleep (sleep percentage)
- removed simplevoicechat

# [v1.0.1] 
### fixes

- permission fixes for starter / rct

# [v1.0.0] 
### First NeoForge Release

- The first modpack in the Modified Cobblemon Series / lineup of modpacks.

- Similar to the popular Modified Cobblemon: PLUS, but with 200 less mods, its a tailored vanilla+ Experience with cobblemon!

- A great introduction to modded minecraft & cobblemon mod!


---

### [Jump to the Top](https://github.com/ModifiedMC/Cobblemon/blob/main/Documentation/Changelogs/Modpacks/Essentials/changelog.md#modified-cobblemon-essentials---master-changelog)
