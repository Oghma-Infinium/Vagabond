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
  - [Patreon DLSS and ENB Binaries](#patreon-dlss-and-enb-binaries)
    - [Installing DLSS](#installing-dlss)
    - [Installing Patreon ENB binaries](#installing-patreon-enb-binaries)
  - [Changing Resolution](#changing-resolution)
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

 1. **Dark Souls Underwear - Never Nude Bodyslide Generated files**: Enabled by default. Disable this mod if you wish to have a nude body.
      > Only for female characters.

 2. **3BA less bounce**: Enabled by default. Disable this mod if you want your 3BA body to jiggle more.
      > Only for female characters.

 3. **[NoDelete] Skyrim Priority My Setting**: These are my personal settings for [Skyrim Priority](https://www.nexusmods.com/skyrimspecialedition/mods/50129). If you wish to edit this to accomodate for your PC specs, please read the `PriorityMod.toml` file within the mod.
      > If you have no clue how to edit this file, do not touch this mod.

 4. **ENB Preset Options:** By default, the list comes with Bjorn ENB enabled. Under the `ENB Preset Options` separator, you may untick the `Bjorn ENB` mod and enable **one** of the 3 optional ENBs depending on what you prefer.


## Patreon DLSS and ENB Binaries

Playing this modlist will **never** require using paid mods, however this guide is for those who are willing to drop a few bucks for improved performance on GPU limited systems.

There are two paywalled mods, which can provide a significant performance increase. The perfromance increase is most noticeable on GPU-limited systems as opposed to CPU-limited ones. Notably, DLSS can even provide small reduction in VRAM usage (estimated roughly 10-20% on performance mode in DLSS.)

Please check if your graphics card is compatible with DLSS before choosing to buy it.

- [ENB-compatible DLSS by Puredark](https://www.patreon.com/PureDark)
- [Optimized ENB binaries by Boris Vorontsov](https://www.patreon.com/enb)

If you choose to get either of these, you need to subscribe to the author's Patreon with the subscription tier that grants access to their paywalled content. As of writing this, it seems to be the $5 tier for both Puredark and Boris Vorontsov but make sure to read the Patreon tiers yourself in case this changes.
  > **NOTE:** I am not responsible for any issues you have with Patreon's payment system or getting the files from the Patreon's discord once you subscribe.

### Installing DLSS

⚠ **Combining Reshade and DLSS is not officially supported and I will not assist with that.** ⚠

Simply drag and drop the DLSS archive you downloaded to the bottom of MO2's left pane and install it like any other mod, then tick the box next to it to enable it. You can keep it at the very bottom of the list. I recommend prefixing the mod's name with `[NoDelete]` so you don't need to reinstall DLSS every time you update the list.

**You do not need to adjust the `SSEDisplayTweaks.ini` or `Skyrim.ini` settings per Puredark's instructions. My default settings for the modlist support DLSS.**

You can find the configuration file for DLSS in the `SKSE\Plugins\` folder of the mod. I recommend turning off sharpening, but **do not** touch either of the MipLodBias settings.

### Installing Patreon ENB binaries

Please follow the steps below to install the Patreon ENB binaries:

1. Create a mod called `[NoDelete] Optional ENB Patreon Binaries` by right-clicking under the `Optionals` separator in the left pane of MO2 -> clicking `All Mods` -> and then clicking `Create empty mod above`.
2. Once you've created the mod, right-click the mod name and click `Open in Explorer`.
3. Once the window opens, create a folder named `Root` and open this folder.
4. Open the archive you got from Boris' discord and open the `WrapperVersion` folder.
5. Drag and drop **only** the `d3d11.dll` and `d3dcompiler_46e.dll` files into the folder called Root that we opened in Step 3.
6. Enable the mod `[NoDelete] Optional ENB Patreon Binaries` in MO2 by ticking the box next to it.
7. If you have opened the game before installing these ENB binaries, open MO2's `Overwrite` by double-clicking the red `Overwrite` text at the very bottom of MO2's left pane.
8. Open the `Root` folder inside Overwrite and delete any `enbcache` and `gpucache` folders if they exist.

## Changing Resolution

By default, Wabbajack will set the resolution in your `Skyrimprefs.ini` to match the native resolution of your monitor. However, Skyrim scales very poorly at resolutions above 1080p (`1920x1080`) and depending on your hardware, it might be difficult to achieve consistent FPS on higher resolutions.

The preferable way to change your resolution is to find the `SSEDisplayTweaks.ini` located in the `SSE Display Tweaks` mod. Open the file and navigate to the `[Render]` section and find the lines `#Resolution=1920x1080`. Here you can change the resolution to your desired resolution. After changing the resolution, remove the `#` in order for the settings to take affect when launching the game.

Example for how the .ini line should look:

**Before:** `#Resolution=1920x1080`  
**After:** `Resolution=2560x1440`

## In-Game MCM options

If an MCM for a mod is **not** mentioned in this section, it may or may not be safe to customize. **Only MCM settings specifically mentioned in this section are officially supported to be adjusted.**

 - **Skyrim Unbound**: You can change your start settings here. 
      >**Do not** choose a werewolf or vampire start, these are known to cause issues.

 - **SmoothCam**: Try out various presets included if you don't like the default camera preset.

 - **One Click Power Attack**: Set your power attack key here. Controller players can keep the default settings.
      > **Do not** bind any keys to dual power attack, it does not do anything with MCO. **Do not** set up the power attack to play on button combos. 
	- **Note:** Power attack and wait keybinds must be the same or some combat functionality will break. Waiting only works when in the tween menu, so these don't interfere with each other.

 - **Skyrim Outfit System**: You can enable the mod and create your own outfits here that can override the visuals of your current equipped gear but retain the stats.

## Wheeler

This section has been written because it is commonly asked enough that I feel I need to write it down on the list's documentation to have an easy place to point people. Almost this entire section is copy-pasted from the [Wheeler Mod Page](https://www.nexusmods.com/skyrimspecialedition/mods/97345).

### Wheel Editing

Changes to the wheel can be made when you open the wheel in either the inventory or magic menu. When you open the wheel in these two menus, the background will grey out, suggesting that you're now in **edit mode**.

#### Creation

By default, create an empty wheel using the "N" key and an empty slot using the "M" key. You can create as many wheels and as many slots in a single wheel as you'd like.

#### Insertion

To insert an item or magic into the slot, hover on the item you desire in the inventory, open the wheel, and left-click (right shoulder) on the entry you wish to insert the item into.

#### Ordering

To change a slot's order in a wheel, press the up/down arrow to swap its position with neighboring slots.

To change a wheel's ordering among all wheels, press the left/right arrow to swap its position with neighboring wheels.

#### Deletion

To delete an item from a slot, simply right-click on the item you wish to delete.

Right-clicking on an empty slot deletes the slot.

Right-clicking on an empty wheel deletes the wheel (you can't delete the last wheel).