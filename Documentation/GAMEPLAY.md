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

Before reading this section, I suggest looking over the [load order](https://loadorderlibrary.com/lists/vagabond) and [keybinds](https://github.com/Oghma-Infinium/Vagabond/blob/main/images/keyboard-layout_Vagabond.jpg) or [gamepad binds](https://github.com/Oghma-Infinium/Vagabond/blob/main/images/controlmap3.png).

## Core Mods

- Perk overhaul for the list is [Vokriinator Black](https://www.nexusmods.com/skyrimspecialedition/mods/26702) which combines perks from [Ordinator](https://www.nexusmods.com/skyrimspecialedition/mods/1137), [Vokrii](https://www.nexusmods.com/skyrimspecialedition/mods/26176), [Adamant](https://www.nexusmods.com/skyrimspecialedition/mods/30191), [SPERG](https://www.nexusmods.com/skyrimspecialedition/mods/14180) and [Path of Sorcery](https://www.nexusmods.com/skyrimspecialedition/mods/6660)
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
  - The mod automatically saves every 15 minutes, but it waits until the game state is safe for saving.
  - You can also manually request save with F5. If the save doesn't happen immediately it means the game state is not safe for saving.
- Do not enable autosaves. They can often save the game at troublesome moments like the above.
  > Autosaves created by Skyrim SafeSave System Overhaul, are safe and can be trusted
- Respect the Acheron alternative death system rather than reloading save after dying. Reloading saves after dying in combat is especially dangerous for save health.



### Leveling and Progression

Vagabond uses [Static Skill Leveling](https://www.nexusmods.com/skyrimspecialedition/mods/30410) for leveling skills. I have configured it with my custom settings:
- Gain skill points equal to 10 + 1 * level for each level up, which caps at 50 points at level 40.
- You can only store maximum of 50 per level, therefore **after level 40 you must spend all your skills points at level up or you will waste some points.**
- Skill costs are as follows:
  - 0 to 25: 1
  - 26 to 50: 2
  - 51 to 75: 3
  - 76 to 100: 4

Perks can be obtained by following ways:
- One perk point from level up.
- From doing radiant quests, explained in [Radiant Quest Point system](https://www.nexusmods.com/skyrimspecialedition/mods/67956) modpage.
- From some major quests listed in [Quests Award Perk Points](https://www.nexusmods.com/skyrimspecialedition/mods/33081) modpage.
- From some boss kills with [Perk Point Awards Redux](https://www.nexusmods.com/skyrimspecialedition/mods/40461).
  - Note: Dragon kills don't give perk points due to soul conversion mechanic. Also no boss gives three points, only one.
- From collecting three [Skyshards](https://www.nexusmods.com/skyrimspecialedition/mods/60748?tab=description).
- By converting three dragon souls with Oghma Infinium.
- By spending devotion points at altars accessible in end-game areas in [Vigilant](https://www.nexusmods.com/skyrim/mods/67103) and [Glenmoril](https://www.nexusmods.com/skyrimspecialedition/mods/32998)
  - Note that this mechanic is a bit overpowered, choose yourself if you want to use it.

## List Tweaks

### Stats

- Health regeneration is 0% at base and magicka regeneration at 10%.
  - This only affects **base** regeneration. All regeneration boosts are still as effective as vanilla because the boosts are additive.
  - Food buffs are highly useful to work around the slow regeneration at early levels. Mages should seek to get robes as early as possible.
- Base magicka is 200 instead of 100.
  - The idea is that you start with more reserve magicka than vanilla, but regenerate slower.

### Combat

- Light melee attacks restore 6 to 15 stamina and 3 to 8 magicka on-hit depending on the weapon type, but deal 50% less damage (compared to vanilla) on enemies above 25% stamina.
  - The idea is that light attacks are a tool for sustaining resources with well-timed aggression.
- You take 25% more damage from power attacks when blocking (calculated *after* block mitigation percent).
  - This is to balance out the fact that blocking power attacks costs the same amount of stamina as blocking light attacks.
  - Timed Block perk still allows you to negate all damage from power attacks with a well-timed block.
- Enemies take 50% more damage from behind. Player takes 25% more damage from behind.
  - Enemies can't turn much during attack combos. Use this to your advantage by flanking enemies while they are attacking.
- Ash of War, a special attack for all weapon types is available in powers menu.
  - Some unique artifacts have unique Ash of War. These will be expanded in the future as I update the list.
- [Maxsu Poise](https://github.com/max-su-2019/MaxsuPoise/releases) is the stagger system in the list, with my custom tweaks:
  - Light attacks and ranged attacks inflict a very short small stagger on poise break.
  - Heavy attacks inflict longer large stagger on poise break.
  - Some Ash of War attacks inflict special staggers like knockback.
  - Enchantments that increase your "mass" increase poise.
- [Acheron](https://www.nexusmods.com/skyrimspecialedition/mods/108159?tab=description) handles the death system.
  - After you die you respawn at a nearby location.
  - If the mod can't find a good location, you enter a crawl state for 30 seconds and de-aggro the enemies, after which you stand back up.
  - I highly encourage to respect the death system instead of reloading save after dying. Reloading saves after combat is very bad for save health and risks getting your save corrupted, especially in a modlist this large.

### Perk Tweaks

- Block tree is almost completely overhauled. It includes custom-made timed block mechanic similar to [Valhalla Combat](https://www.nexusmods.com/skyrimspecialedition/mods/64741) with various perks to boost its effectiveness.
  - It is highly recommended to take the first perk in block tree.
- Sneak Tree has custom-made perfect dodge perks, so it is recommended to invest some skill points in to sneak even if you don't plan on playing a stealth build.
  - Note that the exact timing to trigger perfect dodge is not consistent across different enemy attacks. You'll have to learn the timing for each individual attack, or just hope it accidentally triggers.

### Race Tweaks

### Religion Tweaks

### Spell Tweaks

### Vanilla Quest Changes

- First few quests of the main story are skipped. The main quest starts With Way of the Voice after you kill your first dragon.
- Retrieving dragonstone is now part of Whiterun thaneship. To become thane of Whiterun you must retrieve the Dragonstone, complete Gildergreen quest and help ten citizens of Whiterun. Once Gildergreen sapling fully grows, you can become thane of Whiterun.
- [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704) alters many vanilla questlines, including main quest after Way of the Voice. I recommend just reading the entire modpage. (This mod will be remove in a future update)
- [Penitus Oculatus](https://www.nexusmods.com/skyrimspecialedition/mods/21061) and [Destroy the Thieves Guild](https://www.nexusmods.com/skyrimspecialedition/mods/43244) add ways to obtain unique rewards from Dark Brotherhood and Thieves Guild questlines without joining the factions.

## New Content

### New Quests

### Vanilla Quest Expansions and Edits

### Followers

## Tips and Help
