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

- [Optional Configurations](#optional-configurations)
  - [Optional Mods](#optional-mods)
  - [In-Game MCM options](#in-game-mcm-options)
  - [Wheeler](#wheeler)
    - [Wheel Editing](#wheel-editing)
      - [Creation](#creation)
      - [Insertion](#insertion)
      - [Ordering](#ordering)
      - [Deletion](#deletion)

---

# Optional Configurations

The following sections detail the **supported** modifications to the list. Any other modifications should be discussed in the `#🧠│vagabond-modifications` channel of the [Waking Dreams](https://discord.gg/wakingdreams) support server.

## Optional Mods

This section will cover the following Optional Mods that are included as a part of the modlist. Please note that if you enable any of these mods, it is in your best interest to share this information when reporting any potential bugs that you encounter when playing the modlist.

**Only enabling/disabling these mods is supported. Modifying any settings / configurations for optional mods counts as modification and voids support for the list.** The only exception is `Skyrim Priority My Setting` which has instructions on how to configure it.

- **ENB Preset Options:** By default, the list ships with Cabbage ENB for NAT 3. Under the `ENB Preset Options` separator, you may untick the `Cabbage ENB for NAT 3` mod and enable **one** of the 10 optional ENBs depending on what you prefer.
   > If you have opened the game before, delete the `enbcache` and `gpucache` folders inside MO2's `Overwrite\Root` folder. You can find Overwrite by scrolling all the way down in Mod Organizers' left pane and double-clicking the red `Overwrite` text.

- **Nevernude for females**: Enabled by default. Disable this mod if you wish to have a nude body on a female character.  
  
- **Clean Save Auto-reloader**: >utomatically restarts the game when reloading a save, except for the first save load when opening the game. 
  > You can disable this if you want as it is an optional mod, but understand that you do so at your own risk. You should restart the game when reloading saves or you will even eventually corrupt your save.

- **3BA more jiggle**: Enable if you want more body jiggle and bounce for females.

- **Toggle Combat Camera**: Enabled by default. Automatically swaps camera to third person whean unsheating weapons or entering combat.
   > As mentioned in [FAQ](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/FAQ.md#q-can-i-play-the-list-in-first-person), the list is meant to be played in third person and first person specific issues are not supported.

- **NVIDIA Reflex Support**: SKSE plugin which can more than halve render latency. Only works for NVIDIA GPUs.
   > Only for NVIDIA 900 series or later.

- **Skyrim Upscaler - DLAA** - Enable this mod if you'd like better antialiasing. Do not use the DLSS settings since this version **does not work with ENB**.
   > Only for NVIDIA 2000 series or later.
   
   > DLAA and DLSS **cannot** be used together. Do not enable this if you're using Puredark's Patreon DLSS mod.

- **Enable ENB AA**: Enable this mod if you can't use DLAA or DLSS.
  - You can also change bUseTAA=0 to bUseTAA=1 in profiles/Vagabond/Skyrimperfs.ini for even less grainy image.

- **Equipment UI Preset for 1080p**: UI preset for 1080p users. Enable this if you use a 1080p monitor.

- **CPU affinity**: To adjust CPU affinity for your setup, click the `Puzzle Piece` button at the top of MO2 and select `Set CPU Affinity`. Example of the options you need to press are provided [here](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/cpu%20affinity%20example.png).
  > May give small performance improvement. 

## In-Game MCM options

If an MCM for a mod is **not** mentioned in this section, it may or may not be safe to customize. **Only MCM settings specifically mentioned in this section are officially supported to be adjusted.**

- **Skyrim Unbound**: You can change your start settings here.
    >**Do not** choose a werewolf or vampire start, these are known to cause issues.

- **SmoothCam**: Try out various presets included if you don't like the default camera preset.

- **One Click Power Attack**: Set your power attack key here. Controller players can keep the default settings.
    > **Do not** bind any keys to dual power attack, it does not do anything with MCO. **Do not** set up the power attack to play on button combos.

- **[Skyrim Outfit System](https://www.nexusmods.com/skyrimspecialedition/mods/42162)**: You can enable the mod and create your own outfits here that can override the visuals of your current equipped gear but retain the stats.

- **True directional movement:** You can change the target lock button here. By default it's on controller right stick press. If you want to target lock on keyboard or mouse, you must rebind it.

- **DynDOLOD:** Has settings for LOD distances. Lowering those can improve performance significantly. Good settings for performance:
  > - fBlockLevel0Distance = 7500.000000
  > - fBlockLevel1Distance = 70000
  > - fBlockMaximumDistance = 250000
  > - fSplitDistanceMult = 0.75
  > - fTreeLoadDistance = 70000

## Wheeler

This section has been written because it is commonly asked enough that I feel I need to write it down on the list's documentation to have an easy place to point people. Almost this entire section is copy-pasted from the [Wheeler Mod Page](https://www.nexusmods.com/skyrimspecialedition/mods/97345).

### Wheel Editing

Changes to the wheel can be made when you open the wheel in either the inventory or magic menu. Hold down on the D-pad to open. When you open the wheel in these two menus, the background will grey out, suggesting that you're now in **edit mode**.

#### Creation

By default, create an empty wheel using the "N" key or "Y" button and an empty slot using the "M" key or left bumper. You can create as many wheels and as many slots in a single wheel as you'd like.

#### Insertion

To insert an item or magic into the slot, hover on the item you desire in the inventory, open the wheel, and left-click (right shoulder) on the entry you wish to insert the item into.

#### Ordering

To change a slot's order in a wheel, press the up/down arrow to swap its position with neighboring slots. Same with D-pad.

To change a wheel's ordering among all wheels, press the left/right arrow to swap its position with neighboring wheels. Same with D-pad.

#### Deletion

To delete an item from a slot, simply right-click or left bumper on the item you wish to delete.

Right-clicking on an empty slot deletes the slot.

Right-clicking on an empty wheel deletes the wheel (you can't delete the last wheel).
