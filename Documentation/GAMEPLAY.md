![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/Vagabond%20Nexus%20Header%202.png)

<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/95364">Nexus</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond/blob/main/README.md">Installation</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/GAMEPLAY.md">Gameplay Guide<a/> |
  <a href="https://github.com/Oghma-Infinium/Vagabond/blob/main/CHANGELOG.md">Changelog</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/FAQ.md">FAQ</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md">Config</a> |
  <a href="https://loadorderlibrary.com/lists/vagabond">Modlist</a> ]
</p>

---

## Initial Setup

Before reading this guide, please follow the [readme](https://github.com/Oghma-Infinium/Vagabond/blob/main/README.md) as it will answer the vast majority of technical questions related to getting the list setup and running. Be sure to check out the [configuration](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md) page to learn more about the optional tweaks and addons and MCM options.

## Basics

This section will cover the absolute basics of the list. I suggest reading, or skimming all of the linked mod pages in this section if you are unfamiliar with the preceding mods.

Before reading this section, I suggest looking over the [keybinds](https://github.com/Oghma-Infinium/Vagabond/blob/main/images/keyboard-layout_Vagabond.jpg) or [gamepad binds](https://github.com/Oghma-Infinium/Vagabond/blob/main/images/controlmap3.png) (partially outdated) and [load order](https://loadorderlibrary.com/lists/vagabond).

## Core Mods

- Perk overhaul for the list is [Vokriinator Black](https://www.nexusmods.com/skyrimspecialedition/mods/26702) which combines perks from [Ordinator](https://www.nexusmods.com/skyrimspecialedition/mods/1137), [Vokrii](https://www.nexusmods.com/skyrimspecialedition/mods/26176), [Adamant](https://www.nexusmods.com/skyrimspecialedition/mods/30191), [SPERG](https://www.nexusmods.com/skyrimspecialedition/mods/14180) and [Path of Sorcery](https://www.nexusmods.com/skyrimspecialedition/mods/6660)
   > There is also a [neat calculator](https://thehajo.github.io/VokriinatorBlack/#t/10/0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0) for Vokriinator Black. It is a bit outdated though and doesn't include my custom changes to perks.
- [Mannaz](https://www.nexusmods.com/skyrimspecialedition/mods/87219) and [Freyr](https://www.nexusmods.com/skyrimspecialedition/mods/88043) overhaul races and standing stones. Each standing stone has unique effect for every race, so make sure to read the modpages for these!
- [Sacrosanct](https://www.nexusmods.com/skyrimspecialedition/mods/3928) and [Growl](https://www.nexusmods.com/skyrimspecialedition/mods/31245) overhaul vampires and werewolves.
- [Wintersun](https://www.nexusmods.com/skyrimspecialedition/mods/22506) introduces a religion mechanic.
- [MCO - Modern Combat Overhaul](https://modding-guild.com/mod/attack-mcodxp/) is the core mod for melee combat. It overhauls melee attacks to use attack commitment and combo chaining, similar to other modern action games like Elden Ring and Assassin's Creed Valhalla.
- [Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802) is the core content mod of the list. It adds a museum in Solitude where you can display most of the items from Vanilla game as well as many mod-added items. The museum also involves its own questline.

## Saving practices and you

Bad saving practices can quickly corrupt your save with a modlist this large. For this reason we highly recommend to follow good practices for keeping your save health:

- **Do not** "save scum" by saving and reloading frequently, typically more often than every five minutes. If you want to know why this is bad, please check out this [post](https://old.reddit.com/r/skyrimmods/comments/116raxm/psa_engine_bug_when_reloading_saves/).
- **Do not** play the game at a lower framerate than 30 fps, if this is a problem for you regularly, consider another list.
- **Avoid** saving the game when in a combat state, moving at high speeds, or transitioning through cells (using doors). Other examples of when to avoid saving include active dialogue, crafting, TFC-mode screenshots, or animations.
- Trust the [Skyrim SafeSave System Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/70179) to handle your saves.
  > The mod automatically saves every 5 minutes, but it waits until the game state is safe for saving.

  > You can also manually request save with F5. If the save doesn't happen immediately it means the game state is not safe for saving.
- Do not enable autosaves. They can often save the game at troublesome moments like the above.  
  > Autosaves created by Skyrim SafeSave System Overhaul, are safe and can be trusted
- [Clean Save Auto-reloader](https://www.nexusmods.com/skyrimspecialedition/mods/88219?tab=description) automatically restarts the game when reloading a save, except for the first save load when opening the game.  
  > You can disable this if you want as it is an optional mod, but understand that you do so at your own risk. You *should* restart the game when reloading saves **or you will even eventually corrupt your save.**
- Do not load saves when caught doing crimes. The list has alternative mechanics to evade bounties.
- To ensure save longevity, ideally you should **always** restart the game before loading a save. This is understandably not ideal because of how long it takes for the list to boot up, but do recognize that loading a save without restarting the game *always* risks breaking something in your save.
- Respect the [Acheron](https://www.nexusmods.com/skyrimspecialedition/mods/108159?tab=description) alternative death system rather than reloading save after dying. Reloading saves after dying in combat is especially dangerous for save health, unless you restart the game before loading a save.



### Leveling and Progression

Vagabond uses [Static Skill Leveling](https://www.nexusmods.com/skyrimspecialedition/mods/30410) for leveling skills. I have configured it with my custom settings:
- Gain skill points equal to 10 + 1 * level for each level up, which caps at 50 points at level 40.
- You can only store maximum of 50 per level, therefore **after level 40 you must spend all your skills points at level up or you will waste some points.**
  > Skill costs are as follows:
  > - 0 to 25: 1
  > - 26 to 50: 2
  > - 51 to 75: 3
  > - 76 to 100: 4

Perks can be obtained by following ways:
- One perk point from level up.
- From doing radiant quests, explained in [Radiant Quest Point system](https://www.nexusmods.com/skyrimspecialedition/mods/67956) modpage.
- From some major quests listed in [Quests Award Perk Points](https://www.nexusmods.com/skyrimspecialedition/mods/33081) modpage.
- From some boss kills with [Perk Point Awards Redux](https://www.nexusmods.com/skyrimspecialedition/mods/40461).
  - Note: Dragon kills don't give perk points due to soul conversion mechanic. Also no boss gives three points, only one.
- From collecting three [Skyshards](https://www.nexusmods.com/skyrimspecialedition/mods/60748?tab=description).
- By spending devotion points at altars accessible in end-game areas in [Vigilant](https://www.nexusmods.com/skyrim/mods/67103) and [Glenmoril](https://www.nexusmods.com/skyrimspecialedition/mods/32998)
  > Note that this mechanic is a bit overpowered, choose yourself if you want to use it.
- By trading dragon souls to an NPC in [Unslaad](https://www.nexusmods.com/skyrimspecialedition/mods/11789)
- Twenty perk potions are placed throughout the world inside or near dungeons and forts.

### General Locations of Perk Potions

<Details>

- Hrothmund's Barrow
- Blind Cliff Bastion
- Temple of Xrib (Sightless Pitt)
- Strange Vessel (Moesring Pass)
- Geirmund's Hall
- Pinewatch Bandit's Sanctuary
- Frostflow Lighthouse
- Liar's Retreat
- Redwater Den
- Dead Men's Respite
- Yngol Barrow
- Bleak Falls Sanctum (Bleak Falls Barrow)
- Ironbind Barrow
- Rebel's Cairn
- Darkshade
- Darklight Chambers
- Saering's Watch 
- Moldering Ruins
- Blackreach Silent City Catacombs
- Broken Tower Redoubt (exterior)

</Details>

## List Tweaks

### Stats

- Health regeneration is 0% at base, magicka regeneration at 10% and stamina regeneration at 50%.
  > This only affects **base** regeneration. All regeneration boosts are still as effective as vanilla because the boosts are additive.

  > Food buffs are highly useful to work around the slow regeneration at early levels. Mages should seek to get robes as early as possible.
- Base magicka is 200 instead of 100.
  > The idea is that you start with more reserve magicka than vanilla, but regenerate slower.
- Player starts with 200 carry weight, but misc items, ingredients, crafting materials and potions weigh nothing.
  > You may still want to store excess stuff in your house, because having too much stuff in inventory will cause the inventory to lag.

### Combat

- Light melee attacks restore 6 to 15 stamina and 3 to 8 magicka on-hit depending on the weapon type, but deal 33% less damage (compared to vanilla) on enemies above 25% stamina.
  > The idea is that light attacks are a tool for sustaining resources with well-timed aggression.
- Enemy stamina can be seen from the orange bar below the compass when targeting an enemy. More full -> less stamina the opponent has.
  > There are also perks in Block tree tied to enemy stamina (Posture Break and Deathblow)
- You take 25% more damage from power attacks when blocking (calculated *after* block mitigation percent).
  > This is to balance out the fact that blocking power attacks costs the same amount of stamina as blocking light attacks.
  > Timed Block perk still allows you to negate all damage from power attacks with a well-timed block.
- Enemies take 50% more damage from behind. Player takes 25% more damage from behind.
  > Enemies can't turn much during attack combos. Use this to your advantage by flanking enemies while they are attacking.
- Ash of War, a special attack for all weapon types is available in powers menu.
  > Some unique artifacts have unique Ash of War. These will be expanded in the future as I update the list.
- [Maxsu Poise](https://github.com/max-su-2019/MaxsuPoise/releases) is the stagger system in the list, with my custom tweaks:
  > Light attacks and ranged attacks inflict a very short small stagger on poise break.
  > Heavy attacks inflict longer large stagger on poise break.
  > Some Ash of War attacks inflict special staggers like knockback.
- [Oblivion-like Spell Casting](https://www.nexusmods.com/skyrimspecialedition/mods/65398) allows you to caste spells without equiping them on your hands. Read up the mod page for more info.
  > This mod is a little jank sometimes. Don't try to spam spells too quickly or it will get "stuck" and you'll have wait few seconds for it to work again.
- [Acheron](https://www.nexusmods.com/skyrimspecialedition/mods/108159?tab=description) handles the death system.
  > After you die you either: 
  >  -  respawn at a nearby location. 
  >  -  Enter a crawl state for 30 seconds and de-aggro the enemies, after which you stand back up.  
  >   
  
  >  I highly encourage to respect the death system instead of reloading save after dying. Reloading saves after combat is very bad for save health and risks getting your save corrupted, especially in a modlist this large.

### Crime

- [Crime Bounty Decay SE](https://www.nexusmods.com/skyrimspecialedition/mods/25457) makes bounties slowly decay by default. You can speed that up with some perks.  
- [Book of Shadows](https://www.nexusmods.com/skyrimspecialedition/mods/76086) adds a mask mechanic for evading bounties. When wearing a mask, the bounty accumulates for the mask only. When not wearing the mask, your bounty is not recognized by guards.  
  > You can craft a mask at tanning rack.

### Perk Tweaks

- Block tree is almost completely overhauled. It includes custom-made timed block mechanic similar to [Valhalla Combat](https://www.nexusmods.com/skyrimspecialedition/mods/64741) with various perks to boost its effectiveness.
  - It is highly recommended to take the first perk in block tree.
- Sneak Tree has custom-made perfect dodge perks, so it is recommended to invest some skill points in to sneak even if you don't plan on playing a stealth build.
  - Note that the exact timing to trigger perfect dodge is not consistent across different enemy attacks. You'll have to learn the timing for each individual attack, or just hope it accidentally triggers.

## New Content

### Vanilla Quest Changes

- First few quests of the main story are skipped. The main quest starts With Way of the Voice after you kill your first dragon. Dragon Rising quest doesn't exist
  - Dragons start spawning at word walls after level 15  and rest of the world after level 20.
- Retrieving dragonstone is now part of Whiterun thaneship. To become thane of Whiterun you must retrieve the Dragonstone, complete Gildergreen quest and help ten citizens of Whiterun. Once Gildergreen sapling fully grows, you can become thane of Whiterun.
- [The Choice is Yours](https://www.nexusmods.com/skyrimspecialedition/mods/3850) gives you the freedom to reject quests you may not want to take at the time.
- [Penitus Oculatus](https://www.nexusmods.com/skyrimspecialedition/mods/21061) and [Destroy the Thieves Guild](https://www.nexusmods.com/skyrimspecialedition/mods/43244) add ways to obtain unique rewards from Dark Brotherhood and Thieves Guild questlines without joining the factions.

### Other Vanilla Quest Expansions

- [Bring Meeko To Lod](https://www.nexusmods.com/skyrimspecialedition/mods/25246)
- [Search and Seizure - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/67066)
- [College of Winterhold - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/66666)
- [Caught Red Handed - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/65708)
- [The Heart of Dibella - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/94863)
- [Deceive Degaine](https://www.nexusmods.com/skyrimspecialedition/mods/51863)
- [The Only Cure - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/57683)
- [The Whispering Door - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/76606)
- [Paarthurnax - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/51711)
- [House of Horrors - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/57285)
- [Nilheim - Misc Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/53792)
- [Boethiah for Good Guys](https://www.nexusmods.com/skyrimspecialedition/mods/329)
- [Defeat the Dragon Cult](https://www.nexusmods.com/skyrimspecialedition/mods/86625)
- [Innocence Lost - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/80974)
- [The Brotherhood of Old - Dark Brotherhood Continued](https://www.nexusmods.com/skyrimspecialedition/mods/15322)
- [ACDB - Additional Contracts for the Dark Brotherhood](https://www.nexusmods.com/skyrimspecialedition/mods/59211)
- [Unmasking Sybille](https://www.nexusmods.com/skyrimspecialedition/mods/109265)
- [Blood on the Ice Redux SE](https://www.nexusmods.com/skyrimspecialedition/mods/6126)
- [Save the Icerunner - Lights Out Alternate Routes](https://www.nexusmods.com/skyrimspecialedition/mods/34681)
- [Get both rewards from Clavicus Vile's quest](https://www.nexusmods.com/skyrimspecialedition/mods/43574)

### New Lands

- Vicn Trilogy:
  - [Vigilant](https://www.nexusmods.com/skyrimspecialedition/mods/11849) requires completion of [Kindred Judgment](https://en.uesp.net/wiki/Skyrim:Kindred_Judgment) (Dawnguard DLC main story) and [House of Horrors](https://en.uesp.net/wiki/Skyrim:The_House_of_Horrors)
  - [Glenmoril](https://www.nexusmods.com/skyrimspecialedition/mods/32998) requires completion of [At the Summit of Apocrypha](https://en.uesp.net/wiki/Skyrim:At_the_Summit_of_Apocrypha) (Dragonborn DLC main story) and [Discerning the Transmundane](https://en.uesp.net/wiki/Skyrim:Discerning_the_Transmundane)
    - This quest mod is not finished yet. Play at your own discretion.
  - [Unslaad](https://www.nexusmods.com/skyrimspecialedition/mods/11789) requires completion of [Dragonslayer](https://en.uesp.net/wiki/Skyrim:Dragonslayer) (main quest)
- [Skyrim Extended Cut - Saints and Seducers](https://www.nexusmods.com/skyrimspecialedition/mods/72772)
- [Wyrmstooth](https://www.nexusmods.com/skyrimspecialedition/mods/45565)
- [Beyond Skyrim - Bruma SE](https://www.nexusmods.com/skyrimspecialedition/mods/10917)
- [The Gray Cowl of Nocturnal](https://www.nexusmods.com/skyrimspecialedition/mods/4509)
- [Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/4155)

### New Quests

- [The Tools of Kagrenac](https://www.nexusmods.com/skyrimspecialedition/mods/14168)
- [SIRENROOT - Deluge of Deceit](https://www.nexusmods.com/skyrimspecialedition/mods/70917)
- [Meridia's Order](https://www.nexusmods.com/skyrimspecialedition/mods/102584)
- [Baba Yaga and the Labyrinth](https://www.nexusmods.com/skyrimspecialedition/mods/84492)
- [The Welkynar Knight](https://www.nexusmods.com/skyrimspecialedition/mods/89510)
- [Leaps of Faith](https://www.nexusmods.com/skyrimspecialedition/mods/53074)
- [Skyrim on Skooma](https://www.nexusmods.com/skyrimspecialedition/mods/80975)
- [Belethor's Sister](https://www.nexusmods.com/skyrimspecialedition/mods/92381)

### New Dungeons

- [EasierRider's Dungeon Pack](https://www.nexusmods.com/skyrimspecialedition/mods/2218)
- [Luftahraan Dungeon Pack](https://www.nexusmods.com/skyrimspecialedition/mods/85807)
- [Depths of the Reach](https://www.nexusmods.com/skyrimspecialedition/mods/77718)
- [The Grand Paladin](https://www.nexusmods.com/skyrimspecialedition/mods/46867)
- [The Final Cataclysm](https://www.nexusmods.com/skyrimspecialedition/mods/33167)
- [Glamoril - The Maze of Labyrinthian](https://www.nexusmods.com/skyrimspecialedition/mods/43477)
- [The Midden - Expanded](https://www.nexusmods.com/skyrimspecialedition/mods/2219)
- [Taarengrav Barrow](https://www.nexusmods.com/skyrimspecialedition/mods/84371)
- [Morthal Barrow](https://www.nexusmods.com/skyrimspecialedition/mods/90737)




## Tips and Help
