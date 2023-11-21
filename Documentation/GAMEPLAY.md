![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/Vagabond%20Nexus%20Header%202.png)

<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/95364">Nexus</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond/blob/main/README.md">Installation</a> |
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

### Leveling and Progression

Vagabond uses [Static Skill Leveling](https://www.nexusmods.com/skyrimspecialedition/mods/30410) for leveling skills. I have configured it with my custom settings:
- Gain skill points equal to 10 + 1 * level for each level up, which caps at 50 points at level 40.
- You can only store maximum of 50 per level, therefore **after level 40 you must spend all your skills points at level up or you will waste some points.**
- Skill costs are as follows:
  - 0 to 25: 1
  - 26 to 50: 2
  - 51 to 75: 3
  - 76 to 100: 4
  - **Note:** current version by mistake has last two tiers reversed, feel free to correct this in Static Skill Leveling MCM. Will be fixed in update 1.1.4.

Perks can be obtained by following ways:
- One perk point from level up.
- From doing radiant quests, explained in [Radiant Quest Point system](https://www.nexusmods.com/skyrimspecialedition/mods/67956) modpage.
- From some major quests listed in [Quests Award Perk Points](https://www.nexusmods.com/skyrimspecialedition/mods/33081) modpage.
- By converting three dragon souls with Oghma Infinium.
- From some boss kills with [Perk Point Awards Redux](https://www.nexusmods.com/skyrimspecialedition/mods/40461).
  - Note: Dragon kills don't give perk points due to soul conversion mechanic. Also no boss gives three points, only one.
- From collecting three [Skyshards](https://www.nexusmods.com/skyrimspecialedition/mods/60748?tab=description).
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

- Light melee attacks restore 6 to 20 stamina and 2 to 8 magicka on-hit depending on the weapon type, but deal 50% less damage (compared to vanilla) on enemies that are above 25% stamina.
  - The idea is that light attacks are a tool for sustaining resources with well-timed aggression.
- You take 25% more damage from power attacks when blocking (calculated *after* block mitigation percent).
  - This is to balance out the fact that blocking power attacks costs the same amount of stamina as blocking light attacks.
  - Timed Block perk still allows you to negate all damage from power attacks with a well-timed block.
- Enemies take 50% more damage from behind. Player takes 25% more damage from behind.
  - Enemies can't turn much during attack combos. Use this to your advantage by flanking enemies while they are attacking.

### Perk Tweaks

- Block tree is almost completely overhauled. It includes custom-made timed block mechanic similar to [Valhalla Combat](https://www.nexusmods.com/skyrimspecialedition/mods/64741) with various perks to boost its effectiveness.

### Race Tweaks

### Religion Tweaks

### Spell Tweaks

### Vanilla Quest Changes

## New Content

### New Quests

### Vanilla Quest Expansions and Edits

### Followers

## Tips and Help
