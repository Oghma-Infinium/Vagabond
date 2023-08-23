![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/banner.png)

<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/95364">Nexus</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond/blob/main/README.md">Installation</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond/blob/main/CHANGELOG.md">Changelog</a> |
  <a href="https://loadorderlibrary.com/lists/vagabond">Modlist</a> ]
</p>

---

# Installation

**Modlist Support: [Waking Dreams](https://discord.gg/4WwqfK5yHg)**

***Vagabond requires the full AE upgrade, which means you must purchase the AE edition of the game for the list to function.***

# Contents
- [Installation](#installation)
- [Contents](#contents)
  - [Introduction](#introduction)
    - [System Requirements](#system-requirements)
  - [Installation](#installation-1)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistribution Package](#installing-microsoft-visual-c-redistribution-package)
      - [Pagefile and crash prevention](#pagefile-and-crash-prevention)
      - [Setting Shader Cache Size](#setting-shader-cache-size)
      - [Steam Setup](#steam-setup)
      - [Game Language](#game-language)
      - [Installing Creation Club Content](#installing-creation-club-content)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing Vagabond](#downloading-and-installing-vagabond)
    - [Problems with installation](#problems-with-installation)
  - [Post-Installation and Optional Setup](#post-installation-and-optional-setup)
    - [Verify Install](#verify-install)
    - [Game Folder](#game-folder)
    - [Antivirus Exceptions](#antivirus-exceptions)
    - [Controller and Gamepad Setup](#controller-and-gamepad-setup)
  - [Playing the List](#playing-the-list)
    - [Starting the Game](#starting-the-game)
    - [In-Game MCM options](#in-game-mcm-options)
    - [(Optional) Patreon DLSS and ENB binaries](#optional-patreon-dlss-and-enb-binaries)
  - [Updating the modlist](#updating-the-modlist)
  - [Frequently Asked Questions](#frequently-asked-questions)
  - [Known Issues](#known-issues)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact](#contact)
  - [Credits and Thanks](#credits-and-thanks)


## Introduction

Vagabond is a Skyrim modlist for Anniversary Edition with focus on visuals, modern combat, and Legacy of the Dragonborn. Enairim suite is chosen for most gameplay overhauls, including Vokriinator Black for perks. Wide array of monster, weapon, armor, spell and location overhauls are included to make the world more diverse. This list has full seasons support, including unfreezing of snowy areas during summer.

The full modlist can be viewed [here](https://loadorderlibrary.com/lists/vagabond).

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

### System Requirements

>  Please note these specs are the best idea of a baseline that I can provide at the current moment, based on feedback I have gotten from testers and my own experiences. In the future this will be updated depending on feedback received. That said, **HDD installs are unsupported**.


| Spec Category | My Specs (1440p) | Recommended (1080p) |
|     :---:    |     :---:     |     :---:     
| **CPU**   | i9 9900K @5.0GHz |  R7 3700x / i5 10600k |
| **Video Card**    | 2080ti @1.83Ghz | 3060 Ti / 2070 / 6700 XT |
| **Ram**    | 32gb (2x16) @3.2GHz | 32gb (2x16) |
| **Storage**    | 970 EVO NVMe | SATA SSD |

Downloads: ~291 GB  
Install: ~487 GB  
Temp Files: ~30 GB (on OS drive)  
**TOTAL:** ~780 GB  

 > Wabbajack requires around 30 GB of space on your main OS drive for temporary and working files during the installation, this space is not counted towards the total install space of the list for sake of this guide, however Wabbajack roughly accounts for it in the UI.

## Installation

Installing Vagabond is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating-the-modlist).

### Pre-Installation

These steps are only required for installing the Modlist for the first time. Additionally, many of these steps may be covered in other modlist installs, for new users I suggest reading through here regardless.

#### Installing Microsoft Visual C++ Redistribution Package

 1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v6 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).
 2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
 3. Right click on Skyrim SE and click on properties, untick the "Enable Steam Overlay while in-game."
 4. You also need to start the games to the main menu in order to download all the creations. **DO NOT SKIP THIS STEP, IF YOU DO SO WABBAJACK WILL FAIL**

#### Pagefile and crash prevention

Larger Skyrim modlists require a significant amount of memory, running out of memory **will** result in crashes and other potential issues. Due to Vagabond's size and number of files required to be handled for the list, this step is **NOT** optional, I do not care how much RAM or VRAM you have, please do this step.

 To set up your pagefile:
 1. Press **Win Key + R**
 2. Type *sysdm.cpl ,3* and hit **ENTER**
 3. Navigate to *Performance* and click the box "Settings..."
 4. Click the *Advanced* tab at the top
 5. Under *Virtual Memory* click the box "Change..."
 6. Uncheck *Automatically manage* if it is checked
 7. Select your disk drive, ideally your fastest solid state drive
 8. Click the **Custom size:** button
 9. In the box next to **Initial Size (MB)** type `40960`
 10. In the box next to **Maximum Size (MB)** type `40960`
 11. Click the *Set* button
 12. Click *OK*
 13. Click *Apply*
 14. Click *OK*
 15. Restart your computer in order for your new pagefile to take effect.

#### Setting Shader Cache Size
 Additionally, if you have an NVIDIA GeForce Graphics Card, please do the following: 

 1. Right-click on your desktop and select **NVIDIA Control Panel**
 2. Navigate and click on **Manage 3D settings**. It is the 2nd one to the top.
 3. Scroll down in Global Settings until you see **Shader Cache Size**
 4. Double Click **Driver Default** to the right of Shader Cache Size and select **10 GB**
 5. Click **Apply** in the bottom right hand corner. 
 6. You may exit out of the application.
![](https://raw.githubusercontent.com/iAmMe27/Tahrovin/main/img/ShaderCache.png)

#### Steam Setup

 If you have your Steam Library in Program Files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) and move it elsewhere. Locations such as Desktop, Documents, Downloads, OneDrive, etc. will cause issues with installing and playing the list.

#### Game Language

The English Steam version of Skyrim is the only supported version. I understand that this may be frustrating for non-English speaking users or users with the GOG/Bethesda.net versions, but due to the core file differences between the different versions, I am only able to support one game version.

 1. Right click on your Skyrim in Steam
 2. Click *Properties*
 3. Click *Language*
 4. Set the Language to English.

#### Installing Creation Club Content

 If you have never installed the Creation Club Content before, please do the following:
 1. Purchase the *Skyrim Anniversary Edition* Upgrade from Steam. If you do not do this, you can not install or play the list. 
   > **There is no work around for this and pirating this content will not work. If you pirate the content and come asking for assistance, you will be banned.**
 2. Once you have the Anniversary Edition bought, do the following steps below.
 3. In your Steam Library, right-click on the menu entry for Skyrim, select `Properties` and then select `Local Files`. Click `Verify Integrity of Game Files` and wait.
 4. Once this is completed, launch the game once from Steam. You may receive a prompt that your settings were detected or not detected, this does not matter, nor do any options you select here. Simply open the launcher and launch the game.
 5. Once the intro logo finishes displaying and the Skyrim logo appears, you should receive a prompt to "Download All Content?" Accept this option.
 6. If you did not receive a prompt to download, select the Creation Club option from the menu, and you should find a "Download All" prompt in there somewhere. If this message does not appear, you have not purchased the $20 Upgrade. Begin again from step 1.
 7. Wait for the download process to complete. Do **NOT** ALT-TAB during this process as it will cause the process to fail and you will have to start over again.
 8.  Proceed with the rest of the installation.


### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) on this github and place it in a folder such as `C:\Wabbajack`. **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, OneDrive, etc.), or in your Skyrim's Steam folder**. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Vagabond

Downloading and installing Vagabond can take a while depending on your internet connection and computer. To install Vagabond, complete the following steps.

**VAGABOND'S BETA RELEASE IS ONLY AVAILABLE ON THE [NEXUS PAGE](https://www.nexusmods.com/skyrimspecialedition/mods/95364).**

Until official release, please download the .wabbajack file from the above link.
1. Download the file called **Vagabond** from the Files tab. You **DO NOT** need to download the other files on the page, unless Wabbajack fails to do it later on.
2. Use 7zip to extract the downloaded file. You should now see **Vagabond.wabbajack**.
3. Doubleclick **Vagabond.wabbajack**. Wabbajack should automatically open for you. If it does not, open the Wabbajack app manually and select the **Install from disk** option.
4. Proceed as usual from this point.

**THE BELOW INSTRUCTIONS ARE A PLACEHOLDER FOR OFFICIAL RELEASE, PLEASE REFER TO THE NEXUS INSTRUCTIONS ABOVE**

1. Open Wabbajack and click `Browse Modlists`
2. Press the download button on Vagabond and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Vagabond. **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, etc.), or in your Skyrim's Steam folder**
> The download location does not need to be on a SSD, but it makes installing faster.
4. Press the play button to begin.
5. Turn on your favorite show or a nice long video essay Wabbajack does its thing. Alternatively read through this readme again.
6. If the installation is successful, then rejoice and move onto [post installation](#post-installation-and-optional-setup). If the installation is unsuccessful, follow what is below or join the [discord server](https://discord.gg/WakingDreams) for support.

Sometimes Google Drive and MEGA will experience bandwidth caps, so below I have included the links to the files that require them.
- [High Poly Head](https://drive.google.com/file/d/15_0njBUjHKidNnJPmLXEygzGVWsA3Zbq)
- [BDOR hairs 0.13](https://drive.google.com/file/d/1u85h3rTvR2778AjegtovyLKIhkv-pM1b/edit)
- [BDOR FacePartMod](https://drive.google.com/file/d/1RQl8ki73fgLnzBZn6EWjneuW4Dk8TUO_/edit)
- [Elden Ring - Great Spear](https://drive.google.com/file/d/19muJYVcS_CwVOsQ9bQL_wWsYRz5W7BZI/edit)
- [Elden ring - Legendary Weapons](https://drive.google.com/file/d/11T5k_CAlFMoN9uwWuyRhdRprV7pGHb7n/edit)
- [Full_inu armor pack 02](https://drive.google.com/file/d/12Siwo7JsLw03mJBqXrhHkKOcqPmGPX9k/edit)

Sometimes the SkyrimGuild website also runs into issues so I suggest downloading these in advanced as well.
- [Impactful Blocking](https://www.skyrim-guild.com/s/Impactful-Blocking-14.rar)
- [White Fang Dagger](https://www.skyrim-guild.com/s/White-Fang-Dagger-v1.zip)
- [Valkyrie Sword Redux](https://www.skyrim-guild.com/s/ValkyrieSwordShieldv013.zip)

Patreon downloads incase they give problems.
- List patreon downloads

### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download **X**:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- **X** is not a whitelisted download:

	 - This may happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

- Unable to download `Data_ccXXXXX - *.bsa` or `*.esp`:
	- This error means that there is an issue where Wabbajack is unable to hash your Creation Club Content. If you have followed the steps outlined under [Pre-Installation](#installing-creation-club-content), are not on a pirated copy of the game, and have verified your steam files, then it is very likely that Wabbajack or Bethesda has messed up the hashing for these files. If this is the case, please wait for it to be resolved before continuing to download the list.

- Unable to download `Skyrim_Default.ini`:
 - This error means you failed to follow the readme. Go back to the [game language](#game-language) section and set your game language to English.

## Post-Installation and Optional Setup

### Verify Install

Due to size of the list, the chances of Wabbajack creating corrupted files is higher than usual. This can cause random crashes. It is recommended to follow the steps in [This guide](https://github.com/Oghma-Infinium/Modding-Guides/blob/main/tutorials/Verifying%20your%20Modlist%20Install.md) right after install is done to verify your Vagabond install is clean. If your install has corrupted files delete "mods" folder inside your Vagabond install and run Wabbajack installer for Vagabond again.

### Game Folder

Vagabond uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called `Stock Game`. You don’t need to copy anything at all.

### Antivirus Exceptions

Generally speaking, using Windows Defender is advised as it is a solid antivirus software that will have minimal interference with the game. Antivirus programs can be notorious for false flagging MO2's VFS as problematic, causing crashes or other problems. Antivirus programs like BitDefender, Norton, and Webroot are especially aggressive, and you will very likely need to fully remove them from your PC in order to actually launch the game through MO2.

If you use Windows Defender, it is advised that you set up an Exception for the modlist. To do this follow these steps.
 1. Press the Windows Key.
 2. Type "Windows Defender" in the search bar and select "Windows Security".
 3. Click on "Virus & threat protection" in the left pane.
 4. Click the "Manage settings" option under "Virus & threat protection settings".
 5. Scroll down to "Exclusions" and click "Add or remove exclusions".
 6. Windows Defender will prompt you with a run as administrator screen, just hit yes.
 7. Click the "Add an exclusion" button at the top and choose "Folder".
 8. Navigate to your Install folder for the list and click "Select Folder".
 9. **(OPTIONAL)** You can repeat these steps for the other executables:
    - ModOrganizer.exe (`[Path to Modlist]\ModOrganizer.exe`)
    - Nemesis Unlimited Behavior Engine.exe (`[Path to Modlist]\mods\Project New Reign - Nemesis Unlimited Behavior Engine\Nemesis_Engine\Nemesis Unlimited Behavior Engine.exe`)
    - Synthesis.exe (`[Path to Modlist]\tools\Synthesis\Synthesis.exe`)

### Controller and Gamepad Setup

![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/controlmap.png)

## Playing the List

### Starting the Game
 - Head over to the installation folder and locate an executable named ModOrganizer.exe and launch it.

 1. Launch the "Vagabond" Executable in MO2.
 2. Once the game loads start a new game. You will now spawn in a small room with room with a door in front for you.
 3. (optional) You may adjust MCM settings to your liking, the default settings are for my preferred experience. Refer to MCM options below.
 4. Press enter to create your character. The game will open Racemenu where you can customize your character. Guide for adding presets will be included later.
 6. After you're done with the character creation you'll be presented with a message box. Choose continue to start your journey. Other messages boxes may pop up, just press "ok" on those.

### In-Game MCM options

*If MCM for a mod is not mentioned in this section, it may or may not be safe to customize. Only MCM settings specifically mentioned in this section are officially supported to be adjusted.*

 - **Skyrim Unboound**: You can change your start settings here. **Do not choose werewolf or vampire start these are known to cause issues.**
 - **Smoothcam**: Try out various presets included if you don't like the default camera.
 - **Lamas tinyhud**: Default settings might make the hud widget look wrong on some screen resolutions. Adjust the settings here.
 	- If you play on keyboard and mouse you might want to just completely disable or uninstall Lama's tinyhud as the mod is only useful for controller users.
 - **One click power attack**: Set your power attack key here. Don't bind anything to dual power attack, it doesn't do anything with MCO. Controller players can keep default settings. Also, **Don't set up power attack to play on button combo.**
	- Note: **Power attack and wait keybinds must be the same or some combat functionality will break.** Wait only works in tween menu, so these don't interfere with each other.
 - **Completionist**: This mod gives quite frequent notifications. You can disable them in the HUD section if they bother you.
 - **Skyrim Outfit System**: You can enable the mod and create your own outfits here that can override visuals of your equipped gear but retain the stats.

### (Optional) Patreon DLSS and ENB binaries

*Playing this modlist will **never** require using paid mods, this guide is simply for those who are willing to drop a few bucks for improved performance on GPU limited systems*

There are two paywalled mods, which can provide significant performance increase. The perfromance increase is most noticeable on GPU-limited system as opposed to CPU-limited ones. Notably, DLSS can even provide small reduction in VRAM usage (estimated roughly 10-20% on perforrmance mode in DLSS.)

Please check if your graphics card is compatible with DLSS before choosing to buy it.

- [ENB-compatible DLSS by Puredark](https://www.patreon.com/PureDark)
- [Optimized ENB binaries by Boris Vorontsov](https://www.patreon.com/enb)

If you choose to get either of these, you need to subscribe to the Author's Patreon with the subscription tier that grants access to their paywalled content.
As of writing this, it seems to be the $5 tier for both Puredark and Boris Vorontsov but make sure to read the Patreon tiers yourself in case this changes.
Do note that I'm not responsible if you have issues with the Patreon payment or getting the files from Patreon discord once you subscribe.

**Installing DLSS:**

Simply drag and drop the archive you downloaded to bottom of MO2 left pane and install like any other mod and enable it. You can keep it at the very bottom of the list. I recommend adding [NoDelete] in the mod name so you don't need to reinstall DLSS every time you update.

*You don't need to adjust display tweaks or Skyrim.ini settings like Puredark says, my default settings for the modlist support DLSS*

You can find configuration file for DLSS in the skse\plugins folder of the mod. Don't touch either of the MipLodBias settings. I recommend turning off sharpening.  Combining Reshade and DLSS is not officially supported and I will not assist with that.

**Installing Patreon ENB binaries:**

1. Find the mod called "[NoDelete] Optional ENB Patreon Binaries" in the optionals section of MO2 left pane. (If this doesn't appear create it yourself by right clicking somewhere -> all mods -> create empty mod)
2. Right click the mod and choose "open in explorer".
3. Once the window opens, click the "Root"-folder.
4. Open the archive you got from Boris' discord navigate to "wrapper"-folder.
5. Drag and drop d3d11.dll and d3dcompiler_46e.dll in the Root-folder.
6. Enable the mod "[NoDelete] Optional ENB Patreon Binaries" in MO2
7. If you have opened the game before, open overwrite by clicking the red "overwrite" section at the very bottom of MO2 left pane.
8. Navigate to Root-folder and delete enbcache and gpucache folders if they exist.

## Updating the modlist

Versioning for the list will adhere to the following format: `MAJOR.MINOR.PATCH`.
 - `MAJOR`: Any release with a number change here will be considered a major update as at least 1 area of the list was massively overhauled. These updates with **NEVER** be save safe.
 - `MINOR`: Any release with a number change here will be considered a minor update, these updates will usually not be save safe, unless otherwise specified.
 - `PATCH`: Any release with a number change here will be considered a patch, these updates should be save safe and will be used primarily for bugfixes.
 - In some rare cases you may see a fourth slot be used, which I will refer to as `HOTFIX`. These list "updates" will be used if the list needs to be recompiled for any reason. There will be no changes in these "updates" as they are purely for maintenance.
Before updating, please check the [changelog](https://github.com/Oghma-Infinium/Vagabond/blob/main/CHANGELOG.md) and back up your saves. You may need to start a new game after certain updates.
Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating. To make sure that Wabbajack does not delete your added mods upon updating, prefix your mods with **[NoDelete]**.

**ALWAYS** back up saves before an update. Because of the method Wabbajack uses to include the start save, any save within the profile will be wiped. 

*Please make sure you back up your saves if you plan on continuing a playthrough across a **save safe** update.*

## Frequently Asked Questions

Q: How do I wait?

> A: Open tween menu (tab menu) first.

Q: Can I play the list in first person?

> A: The combat is meant for 3rd person only and I won't support or solve first-person specific issues with combat. You can use first person for casually exploring or picking up items though.

Q: Why can't I attack with my left hand weapon?

> A: MCO doesn't support left hand attack, but if you have a melee weapon in both hands you get a dual wield moveset that alternates between both hands by just pressing right hand attack.

Q: Any video showcase of the list?

> A: [Biggie's Youtube channel has some content.](https://www.youtube.com/@biggie_boss/streams)

Q: A mod in the list doesn't do what it says on the mod page. Is it broken?

> A: Is the mod under the "Assets and resources" -separator in MO2 left pane? If yes, then don't assume anything the mod page says about the mod is true for the list. If its not under assets and sourcers then report a bug to me.

Q: My character's face suddenly became much darker, causing neck seam. What do I do?

> A: Enter and exit racemenu to fix. To enter racemenu, either use vanity mirror in your inventory (recommended, safer) or console command "showracemenu" without the quotes.

## Known Issues
- Tolfdir not getting to Saarthal. Just click him on console, walk to Saarthal and type "prid" in console without the quotes.
- NPCs in Whiterun line up in front of Underforge entrance.

## Removing the Modlist
Simply delete the folder. Congratulations, you have uninstalled Vagabond.

## Contact

**PLEASE DO NOT DM ME ON DISCORD.** If you have an issue with the list, please join the [Waking Dreams](https://discord.gg/4WwqfK5yHg) discord server for support.


## Credits and Thanks

- _YOU_ for reading this.
- [Phoenix](https://github.com/foreverphoenix) for making [Aurora](https://www.nexusmods.com/skyrimspecialedition/mods/89805), which was used as the visual base for the list.
- [aljo](https://ko-fi.com/aljoxo), [Bingus](https://ko-fi.com/beangas), and the rest of the Waking Dreams server for helping me with the list.
- [ElminsterAU](https://www.patreon.com/ElminsterAU) and the xEdit team for SSEEdit.
- Noggog for Mutagen and Synthesis.
- Halgari and the WJ Team for this amazing platform.
- [Cosmofujia](https://www.patreon.com/fujiacosmo) for a significant amount of high quality Weapon Models.
