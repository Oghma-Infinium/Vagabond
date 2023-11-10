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

**Modlist Support: [Waking Dreams](https://discord.gg/wakingdreams)**

## Contents

- [Optional Configurations](#optional-configurations)
  - [Optional Mods](#optional-mods)
  - [Patreon DLSS for ENB](#patreon-dlss-for-enb)
    - [Installing DLSS](#installing-dlss)
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

This section will cover the following Optional Mods that are included as a part of the modlist. Please note that if you do any of these tweaks, it is in your best interest to share this information when reporting any potential bugs that you encounter when playing the modlist.

1. **ENB Preset Options:** By default, the list ships with Amon ENB for NAT 3. Under the `ENB Preset Options` separator, you may untick the `AMON ENB REBORN for NAT 3` mod and enable **one** of the 4 optional ENBs depending on what you prefer.
   > If you have opened the game before, delete the `enbcache` and `gpucache` folders inside MO2's `Overwrite\Root` folder. You can find Overwrite by scrolling all the way down in Mod Organizers' left pane and double-clicking the red `Overwrite` text.

2. **Dark Souls Underwear - Never Nude Bodyslide Generated files**: Enabled by default. Disable this mod if you wish to have a nude body.

3. **3BA Less Bounce**: Enabled by default. Disable this mod if you want your 3BA body to jiggle more.

4. **Equipment UI Preset for 1080p**: UI preset for 1080p users. Enable this if you use a 1080p monitor.

5. **Skyrim Upscaler - DLAA** - Enable this mod if you'd like better antialiasing. Do not use the DLSS settings since this version **does not work with ENB**.
   > DLAA and DLSS **cannot** be used together. Do not enable this if you're using Puredark's Patreon DLSS mod.

6. **Experimental Cell Transition Crash Fix**: Experimental fix for CTDs during cell transitions in interiors. If you find yourself getting these often, feel free to enable this mod.

7. **Skyrim Priority My Setting**: These are my personal settings for [Skyrim Priority](https://www.nexusmods.com/skyrimspecialedition/mods/50129). If you wish to edit this to accommodate for your PC specs, please read the `PriorityMod.toml` file within the mod.
    > If you have no clue how to edit this file, do not touch this mod.



## Patreon DLSS for ENB

Playing this modlist will **never** require using paid mods, however this guide is for those who are willing to drop a few bucks for improved performance on GPU limited systems.

Perfromance increase from DLSS is most noticeable on GPU-limited systems as opposed to CPU-limited ones. Notably, DLSS can even provide small reduction in VRAM usage (estimated roughly 10-20% on performance mode in DLSS.) DLSS frame generation, which is only available on RTX 4000-series cards can also help with CPU bottleneck.

Please check if your graphics card is compatible with DLSS before choosing to buy it.

- [ENB-compatible DLSS by Puredark](https://www.patreon.com/PureDark)

If you choose to get DLSS, you need to subscribe to the author's Patreon with the subscription tier that grants access to their paywalled content. As of writing this, it seems to be the $5 tier for Puredark but make sure to read the Patreon tiers yourself in case this changes.
  > **NOTE:** I am not responsible for any issues you have with Patreon's payment system or getting the files from the Patreon's discord once you subscribe.

### Installing DLSS

⚠ **Combining Reshade and DLSS is not officially supported and I will not assist with that.** ⚠

Simply drag and drop the DLSS archive you downloaded to the bottom of MO2's left pane and install it like any other mod, then tick the box next to it to enable it. You can keep it at the very bottom of the list. I recommend prefixing the mod's name with `[NoDelete]` so you don't need to reinstall DLSS every time you update the list.

**You do not need to adjust the `SSEDisplayTweaks.ini` or `Skyrim.ini` settings per Puredark's instructions. My default settings for the modlist support DLSS.**

You can find the configuration file for DLSS in the `SKSE\Plugins\` folder of the mod. I recommend turning off sharpening, but **do not** touch either of the MipLodBias settings.

## In-Game MCM options

If an MCM for a mod is **not** mentioned in this section, it may or may not be safe to customize. **Only MCM settings specifically mentioned in this section are officially supported to be adjusted.**

- **Skyrim Unbound**: You can change your start settings here.
    >**Do not** choose a werewolf or vampire start, these are known to cause issues.

- **SmoothCam**: Try out various presets included if you don't like the default camera preset.

- **One Click Power Attack**: Set your power attack key here. Controller players can keep the default settings.
    > **Do not** bind any keys to dual power attack, it does not do anything with MCO. **Do not** set up the power attack to play on button combos.

- **Skyrim Outfit System**: You can enable the mod and create your own outfits here that can override the visuals of your current equipped gear but retain the stats.

- **Activation Animations**: You can enable or disable animations for specific actions like looting or opening doors here.

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
