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

# ⚠ This modlist is no longer maintained and cannot be installed. ⚠

**Known issues are documented in [Trello](https://trello.com/b/khix4egd/vagabond-bug-reports).**

## Contents

- [⚠ This modlist is no longer maintained and cannot be installed. ⚠](#-this-modlist-is-no-longer-maintained-and-cannot-be-installed-)
  - [Contents](#contents)
- [FAQ](#faq)
  - [Q: I found a bug. Can you fix it?](#q-i-found-a-bug-can-you-fix-it)
  - [Q: I have feedback. Will it be implemented?](#q-i-have-feedback-will-it-be-implemented)
  - [Q: My game is not opening or keeps crashing or freezing. What can I do?](#q-my-game-is-not-opening-or-keeps-crashing-or-freezing-what-can-i-do)
  - [Q: My performance is bad or I get stutters. What can I do?](#q-my-performance-is-bad-or-i-get-stutters-what-can-i-do)
  - [Q: My CPU and GPU usage is low. Is there something wrong?](#q-my-cpu-and-gpu-usage-is-low-is-there-something-wrong)
  - [Q: Why is the list so performance heavy? Is there a specific mod that causes it?](#q-why-is-the-list-so-performance-heavy-is-there-a-specific-mod-that-causes-it)
  - [Q: Ultrawide support?](#q-ultrawide-support)
  - [Q: Is x mod in the list?](#q-is-x-mod-in-the-list)
  - [Q: Can I play the list in first person?](#q-can-i-play-the-list-in-first-person)
  - [Q: How do I wait?](#q-how-do-i-wait)
  - [Q: How do I open the OAR, IED and dmenu?](#q-how-do-i-open-the-oar-ied-and-dmenu)
  - [Q: Why can't I attack with my left hand weapon?](#q-why-cant-i-attack-with-my-left-hand-weapon)
  - [Q: How do I block with dual wield or spellsword?](#q-how-do-i-block-with-dual-wield-or-spellsword)
  - [Q: Any video showcase of the list?](#q-any-video-showcase-of-the-list)
  - [Q: How can I access features of Elden Rim mod?](#q-how-can-i-access-features-of-elden-rim-mod)
  - [Q: My character's face suddenly became much darker, causing a neck seam. What do I do?](#q-my-characters-face-suddenly-became-much-darker-causing-a-neck-seam-what-do-i-do)
  - [Q: How do I activate survival mode?](#q-how-do-i-activate-survival-mode)
- [Known Issues](#known-issues)
# FAQ

## Q: I found a bug. Can you fix it?

> The list is no longer actively developed so probably not. If the bug is extremely critical preventing gameplay of the list, hotfix might be done, but I doubt such bugs are in the list anymore.

## Q: I have feedback. Will it be implemented?

> No, the list is no longer actively developed.

## Q: My game is not opening or keeps crashing or freezing. What can I do?

> A: There are several reasons that could gause the list to crash or freeze.
> - Make sure you're **not** pressing "unlock" button in MO2 after starting Vagabond.
> - Make sure you have setup [antivirus exceptions properly](https://github.com/Oghma-Infinium/Vagabond/tree/main#antivirus-exceptions). Any other antivirus except Windows Defender may still cause issues.
> - Make sure you've setup [40GB pagefile correctly](https://github.com/Oghma-Infinium/Vagabond/tree/main#pagefile-and-crash-prevention).
> - Make sure you're not using HDD or external SSD to play the list. Only internal SSD installs are supported (NVME, SATA).
> - Make sure you're using supported operating system. Only Windows 10 and 11 operating systems are supported. Remote computer services and custom editions of Windows are not supported. (Including Steam Link)
> - Just try **restarting your PC** before any further troubleshooting steps.
> - If the crash/freeze is one-off and doesn't repeat then I wouldn't worry about it. List this size may have occasional hickup every few hours of gameplay, but if it happens more often than that then there might be an actual issue.
> - If the crash/freeze happens during combat in interiors, it could be that the game engine randomly gave up due to amount of animations and effects happening simultaneously. Some have reported that waiting a few in-game hours has alleviated the issue.
> - If you crash or freeze, it may produce crash log in `\NetScriptFramework\Crash folder in Overwrite`. You can drop it in the support channel in the Waking Dreams Discord.
> - Your save game could be corrupt due to bad saving habbits. Make sure you adhere to good saving practices outlined in [gameplay guide](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/GAMEPLAY.md)
> - Your list install might be corrupted. You may want to backup your saves, delete the install while keeping downloads and reinstall the list.
> - Make sure your GPU drivers are up to date. I recommend choosing clean install when updating. Nvidia card users must redo [gpu cache step](https://github.com/Oghma-Infinium/Vagabond/tree/main#setting-shader-cache-size-nvidia-graphics-cards-only) if clean installing drivers.
> - Close background programs such as iCU or Razer Synapse and any overlays such as Discord overlay.
> - Disable overclocks you may have on your CPU, GPU or RAM or any other components. Other custom tweaks in BIOS could cause issues as well. We recommend to try reseting BIOS to factory settings in such cases.

It doesn't matter if some of these points didn't cause issues in other modlists. Due to size of Vagabond, the modlist is more likely to show symptoms with an enviroment that is generally not friendly with modded Skyrim / Creation Engine.

**These points only apply to completely unmodified install of the list. If you have modified the list in *any way*, then we're not providing official support with any issues you may have.**

If none of these suggestions help with your issue, feel free to reach out to us in Waking Dreams Discord. There is always a possibility that the list has some legitimate, unresolved issue.

## Q: My performance is bad or I get stutters. What can I do?

> A: Vagabond is probably *the heaviest* modlist out there. The solution is to upgrade your PC parts. Some amount of stutters may happen even on powerful PCs when the game loads new cells. Configuring CPU affinity as instructed in [config](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md#optional-mods) may help.

## Q: My CPU and GPU usage is low. Is there something wrong?

> A: No, your CPU usage is low because Skyrim runs on an ancient engine that only supports single-core (main thread) rendering, therefore only one of the cores will be at or close to 100% usage. This will also result in low GPU usage because your GPU can't draw more frames when rendering is bottlenecked by the CPU main thread. This has always been an issue with Skyrim, but the overall performance demand of Vagabond makes the issue more apparent.

## Q: Why is the list so performance heavy? Is there a specific mod that causes it?

> A: The performance heaviness is sum of large amount of mods added to the list. The mod count is not the only factor, but also the *types* of mods added. The list has many mods adding clutter, locations, NPCs, enemies, grass, flora etc. All of the stuff added combined makes this list extremely demanding to run. Diversity of objects also matters, the game engine is observed to be worse at handling diversity of objects even if total count is the same. In conclusion the performance heaviness of the list is result of how the list was built as a whole and can't be pin-pointed on a single mod.

## Q: Ultrawide support?

> A: There is no official ultrawide support for Vagabond. Only screens with standard aspect ratio of 16:9 is supported. Trying to run Vagabond with non-native aspect ratio or resolution of the screen is unsupported. 16:10 screens might work fine as well. 

## Q: Is x mod in the list?

> A: Look at the [load order library](https://loadorderlibrary.com/lists/vagabond).

## Q: Can I play the list in first person?

> A: The list is meant for 3rd person gameplay and I won't support or solve first-person specific issues. By default, a mod called `Toggle Combat Camera` is enabled, which automatically makes you enter third person when drawing a weapon or entering combat.

## Q: How do I wait?

> A: Open the tween menu (press tab) first then press T or RT/R2 on controller.

## Q: How do I open the OAR, IED and dmenu?

> A: These menus have been disabled purposefully. Enabling them and messing with these menus is not officially supported.

## Q: Why can't I attack with my left hand weapon?

> A: MCO doesn't support left hand attacks, but if you have a melee weapon in both hands, you will get a dual wield moveset that alternates between both hands by just pressing right hand attack.

## Q: How do I block with dual wield or spellsword?

> A: With dual wield you block just like you normally would (left bumper or right click). There is no spellsword block. Instead, consider casting spells hands-free with shout casting. (Read [Gameplay Guide](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/GAMEPLAY.md))

## Q: Any video showcase of the list?

> A: [Biggie Boss' Youtube channel has some content](https://www.youtube.com/@biggie_boss/streams). Searching for [`Vagabond Skyrim Modlist`](https://www.youtube.com/results?search_query=vagabond+skyrim+modlist) in Youtube will also give you many results.

## Q: How can I access features of Elden Rim mod?

> A: You don't. Elden Rim is not used in the list, assets and some logic from the plugin are used for other purposes. Don't refer to anything from the elden rim modpage, the mod doesn't "exist" in the list.

## Q: My character's face suddenly became much darker, causing a neck seam. What do I do?

> A: This is a vanilla bug that can be fixed by entering and exiting Racemenu. To enter Racemenu, open console and type in: `showracemenu`, then exit Racemenu immediately.

## Q: How do I activate survival mode?

> A: Survival mode is not supported in Vagabond.

# Known Issues

Known issues are documented in [Trello](https://trello.com/b/khix4egd/vagabond-bug-reports)
