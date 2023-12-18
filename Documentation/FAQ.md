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

**Modlist Support: [Waking Dreams](https://discord.gg/wakingdreams)**

## Contents

- [FAQ](#faq)
  - [Q: My performance is bad or I get stutters. What can I do?](#q-my-performance-is-bad-or-i-get-stutters-what-can-i-do)
  - [Q: My CPU and GPU usage is low. Is there something wrong?](#q-my-cpu-and-gpu-usage-is-low-is-there-something-wrong)
  - [Q: Why is the list so performance heavy? Is there a specific mod that causes it?](#q-why-is-the-list-so-performance-heavy-is-there-a-specific-mod-that-causes-it)
  - [Q: Ultrawide support?](#q-ultrawide-support)
  - [Q: Is x mod in the list?](#q-is-x-mod-in-the-list)
  - [Q: Can you add x mod? Why is x mod not included?](#q-can-you-add-x-mod-why-is-x-mod-not-included)
  - [Q: Can I play the list in first person?](#q-can-i-play-the-list-in-first-person)
  - [Q: How do I wait?](#q-how-do-i-wait)
  - [Q: How do I open the OAR, IED and dmenu?](#q-how-do-i-open-the-oar-ied-and-dmenu)
  - [Q: Why can't I attack with my left hand weapon?](#q-why-cant-i-attack-with-my-left-hand-weapon)
  - [Q: Any video showcase of the list?](#q-any-video-showcase-of-the-list)
  - [Q: How can I access features of Elden Rim mod?](#q-how-can-i-access-features-of-elden-rim-mod)
  - [Q: My character's face suddenly became much darker, causing a neck seam. What do I do?](#q-my-characters-face-suddenly-became-much-darker-causing-a-neck-seam-what-do-i-do)
  - [Q: How do I activate survival mode?](#q-how-do-i-activate-survival-mode)
- [Known Issues](#known-issues)
  - [Tolfdir won't got to Saarthal!](#tolfdir-wont-got-to-saarthal)
  - [Riften house cats talk to me about economy?](#riften-house-cats-talk-to-me-about-economy)
  - [ENB looks weird until opening and closing the map](#enb-looks-weird-until-opening-and-closing-the-map)
  - [Autumn has terrible green snow grass](#autumn-has-terrible-green-snow-grass)
  - [Some NPCs have multiple sets of gear](#some-npcs-have-multiple-sets-of-gear)
  - [Disappearing bridges](#disappearing-bridges)
  - [Weapon damage higher in crafting menus than in inventory](weapon-damage-higher-in-crafting-menus-than-in-inventory)

# FAQ

## Q: My performance is bad or I get stutters. What can I do?

> A: Vagabond is probably *the heaviest* modlist out there. No plans for performance version. Either get better hardware or try another modlist. Some amount of stutters may happen even on powerful PCs when the game loads new cells. Configuring CPU affinity for Skyrim Priority mod as instructed in [config](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md#optional-mods) may help.

## Q: My CPU and GPU usage is low. Is there something wrong?

> A: No, your CPU usage is low because Skyrim runs on an ancient engine that only supports single-core (main thread) rendering, therefore only one of the cores will be at or close to 100% usage. This will also result in low GPU usage because your GPU can't draw more frames when rendering is bottlenecked by the CPU main thread. This has always been an issue with Skyrim, but the overall performance demand of Vagabond makes the issue more apparent.

## Q: Why is the list so performance heavy? Is there a specific mod that causes it?

> A: The performance heaviness is sum of large amount of mods added to the list. The mod count is not the only factor, but also the *types* of mods added. The list has many mods adding clutter, locations, NPCs, enemies, grass, flora etc. All of the stuff added combined makes this list extremely demanding to run. Diversity of objects also matters, the game engine is observed to be worse at handling diversity of objects even if total count is the same. In conclusion the performance heaviness of the list is result of how the list was built as a whole and can't be pin-pointed on a single mod.

## Q: Ultrawide support?

> A: There is no official ultrawide support for Vagabond. Only screens with standard aspect ratio of 16:9 is supported. Trying to run Vagabond with non-native aspect ratio or resolution of the screen is unsupported. 16:10 screens might work fine as well. 

## Q: Is x mod in the list?

> A: Look at the [load order library](https://loadorderlibrary.com/lists/vagabond).

## Q: Can you add x mod? Why is x mod not included?

> A: Probably won't add the mod unless its a bugfix or compatibility mod I was missing. I won't give detailed explanation for each mod on why it was not added. Could be bugs, incompatibility, patching, I simply don't like the mod or I didn't know about the mod (very unlikely if it is a popular mod).

## Q: Can I play the list in first person?

> A: The combat is meant for 3rd person only and I won't support or solve first-person specific issues with combat. You can use first person for casually exploring or picking up items though. By default, a mod called `Seamless Combat Camera` is enabled, which automatically makes you enter third person when drawing a weapon or entering combat.

## Q: How do I wait?

> A: Open the tween menu (press tab) first then press T or RT/R2 on controller.

## Q: How do I open the OAR, IED and dmenu?

> A: These menus have been disabled purposefully. Enabling them and messing with these menus is not officially supported.

## Q: Why can't I attack with my left hand weapon?

> A: MCO doesn't support left hand attacks, but if you have a melee weapon in both hands, you will get a dual wield moveset that alternates between both hands by just pressing right hand attack.

## Q: Any video showcase of the list?

> A: [Biggie Boss' Youtube channel has some content](https://www.youtube.com/@biggie_boss/streams). Searching for [`Vagabond Skyrim Modlist`](https://www.youtube.com/results?search_query=vagabond+skyrim+modlist) in Youtube will also give you many results.

## Q: How can I access features of Elden Rim mod?

> A: You don't. Elden Rim is not used in the list, assets and some logic from the plugin are used for other purposes. Don't refer to anything from the elden rim modpage, the mod doesn't "exist" in the list.

## Q: My character's face suddenly became much darker, causing a neck seam. What do I do?

> A: This is a vanilla bug that can be fixed by entering and exiting Racemenu. To enter Racemenu, open console and type in: `showracemenu`, then exit Racemenu immediately.

## Q: How do I activate survival mode?

> A: Survival mode is not supported in Vagabond.

# Known Issues

## Tolfdir won't got to Saarthal!

> A: Just click him on console, walk to Saarthal, and type `moveto player` in console.

## Riften house cats talk to me about economy?

> A: Bug that is now a feature, won't fix.

## ENB looks weird until opening and closing the map

> A: Known issue. Don't know the cause. Open and close the map when you start the game.

## Autumn has terrible green snow grass

> A: I know, it bothers me a lot. I need to redo grass cache and DynDOLOD to fix this.

## Some NPCs have multiple sets of gear

> A: This is a bug with SPID, won't fix.

## Disappearing bridges

> A: Bug with newer versions of DynDOLOD. Can't fix myself, up to original author of the mod to figure it out.

## Weapon damage higher in crafting menus than in inventory

> A: Known issue. No known fix.
