![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/Vagabond%20Banner%20PNG.png)

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

**Vagabond requires the full AE upgrade, which means you must purchase the AE edition of the game for the list to function!**

# Contents

- [Contents](#contents)
  - [Introduction](#introduction)
    - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Prerequisites](#prerequisites)
      - [Pagefile and Crash Prevention](#pagefile-and-crash-prevention)
      - [Setting Shader Cache Size (NVIDIA Graphics Cards Only)](#setting-shader-cache-size-nvidia-graphics-cards-only)
      - [Steam Setup](#steam-setup)
      - [Game Language](#game-language)
      - [Installing Creation Club Content](#installing-creation-club-content)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing Vagabond](#downloading-and-installing-vagabond)
      - [Problematic Files](#problematic-files)
    - [Problems with Installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [⚠ Verify Install ⚠](#-verify-install-)
    - [Antivirus Exceptions](#antivirus-exceptions)
    - [Controller Keybinds](#controller-keybinds)
  - [Playing the List](#playing-the-list)
    - [Starting the Game](#starting-the-game)
  - [Updating the modlist](#updating-the-modlist)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact](#contact)
  - [Credits and Thanks](#credits-and-thanks)

## Introduction

Vagabond is a modlist for Skyrim Anniversary Edition with a focus on visuals, modern combat, and Legacy of the Dragonborn. EnaiRim suite is chosen for most gameplay overhauls, including Vokriinator Black for perks. A wide array of monster, weapon, armor, spell and location overhauls are included to make the world more diverse. This list also has full seasons support, including unfreezing of snowy areas during Summer.

If you're curious about the specific mods in the list, the full modlist can be viewed [here](https://loadorderlibrary.com/lists/vagabond).

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

### System Requirements

> Please note these specs are the best idea of a baseline that I can provide at the current moment, based on feedback I have gotten from testers and my own experiences. In the future this will be updated depending on feedback received. With that said, **HDD installs are absolutely not supported**.

| Spec Category | My Specs (1440p DLSS Performance Preset) | Recommended (1440p) |
|     :---:    |     :---:     |     :---:
| **CPU**   | i9 9900K @5.0GHz |  R7 5800X / i5 12600k |
| **Video Card**    | 2080ti @1.83Ghz | 4070 Ti / 7700 XT |
| **Ram**    | 32GB (2x16) @3.2GHz | 32GB (2x16) |
| **Storage**    | 970 EVO NVMe | SATA/NVME SSD |

At least 10GB of VRAM on GPU is recommended for the list, otherwise you'll experience frequent stutters in exteriors.

Downloads: ~290 GB  
Install: ~460 GB  
Temp Files: ~30 GB (on OS drive)  
**TOTAL:** ~780 GB  

 > Wabbajack requires around 30 GB of space on your main OS drive for temporary and working files during the installation. The total size after installation is done is closer to 750 GB.

## Installation

⚠ **Vagabond requires the full AE upgrade, which means you must purchase the AE edition of the game for the list to function!** ⚠

If you are updating the modlist, you can safely skip to the [updating section](#updating-the-modlist).

### Pre-Installation

These steps are only required for installing the modlist for the first time. Additionally, many of these steps may be covered in other modlist installs, but for new users I suggest reading through here regardless.

#### Prerequisites

 1. (Soft Requirement) A Nexus Premium account is recommended. Without Premium, you will need to manually click the `Slow Download` button for each mod.
 
 2. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe) & [.Net Runtime v6 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).

 3. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).

 4. Right click on Skyrim SE and click on properties, untick the `Enable Steam Overlay while in-game` option.

 5. Remove or disable any 3rd party antivirus such as Webroot or Bitdefender. These programs **will absolutely** cause issues with your Vagabond installation due to how MO2's Virtual File Staging works.

#### Pagefile and Crash Prevention

Larger Skyrim modlists require a significant amount of memory and running out of memory **will** result in crashes and other potential issues. Due to Vagabond's size and number of files required to be handled for the list, this step is **NOT** optional. I do not care how much RAM or VRAM you have, **please** do this step.

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

#### Setting Shader Cache Size (NVIDIA Graphics Cards Only)

 Additionally, if you have an NVIDIA GeForce Graphics Card, please do the following:

 1. Right-click on your desktop and select **NVIDIA Control Panel**
 2. Navigate and click on **Manage 3D settings**. It is the 2nd one to the top.
 3. Scroll down in Global Settings until you see **Shader Cache Size**
 4. Double Click **Driver Default** to the right of Shader Cache Size and select **10 GB**
 5. Click **Apply** in the bottom right hand corner.
 6. You may exit out of the application.
![](https://raw.githubusercontent.com/iAmMe27/Tahrovin/main/img/ShaderCache.png)

#### Steam Setup

 If you have your Steam Library inside your Program Files folder, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) and move it elsewhere. Locations such as Desktop, Documents, Downloads, OneDrive, etc. will cause issues with installing the list.

#### Game Language

The English Steam version of Skyrim is the only supported version. I understand that this may be frustrating for non-English speaking users or users with the GOG versions, but due to the core file differences between the different versions, I am only able to support one game version.

To set your Skyrim language to English:

 1. Right click on your Skyrim in Steam
 2. Click `Properties`
 3. Click the drop down box next to `Language`
 4. Set the language to English.

#### Installing Creation Club Content

 If you have never installed the Creation Club Content before, please do the following:

1. Purchase the [`Skyrim Anniversary Edition Upgrade`](https://store.steampowered.com/app/1746860/The_Elder_Scrolls_V_Skyrim_Anniversary_Upgrade/) from Steam. **If you do not do this, you can not install or play the list.**
    > There is no work around for this and pirating this content will **not** work. If you pirate the content and come asking for assistance, you will be banned.

2. In your Steam Library, right-click on the menu entry for Skyrim, select `Properties` and then select `Installed Files`. Click `Verify Integrity of Game Files` and wait for it to complete.

3. Once this is completed, launch the game once from Steam. You may receive a prompt that your settings were detected or not detected, this does not matter, nor do any options you select here. Simply open the launcher and launch the game.

4. Once the intro logo finishes displaying and the Skyrim logo appears, you should receive a prompt to `Download All Content?` Accept this option.

5. If you did not receive a prompt to download, select the Creation Club option from the menu and you should find a "Download All" prompt in there somewhere. If this message does not appear, you have not purchased the $20 Upgrade. Begin again from step 1.

6. Wait for the download process to complete. Do **NOT** ALT-TAB during this process as it will cause the process to fail and you will have to start over again.

7. Proceed with the rest of the installation.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, follow these steps to install Wabbajack:

1. Create an empty folder named `Wabbajack` on the root of your drive, such as `C:\Wabbajack` for example. **DO NOT set the folder to Program Files, User protected folders (such as Desktop, Documents, Downloads, etc.), or in your Skyrim's Steam folder**.
   > The `Wabbajack` folder does not need to be on an SSD, but it makes installing faster. You can create a `Wabbajack` folder on an HDD instead for the sake of saving space.

2. Download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place the `Wabbajack.exe` file inside the Wabbajack folder you created in Step 1.

3. Double-click the `Wabbajack.exe` file that is now inside your Wabbajack folder to set up the program.

#### Downloading and Installing Vagabond

Downloading and installing Vagabond can take a while depending on your internet connection, PC specs, and if you have Nexus Premium. Without Premium, you will need to manually click the `Slow Download` button for each mod.

To install Vagabond, complete the following steps:

1. Open Wabbajack and click `Browse Modlists`
   
2. Tick on the `Show Unofficial lists` box in the top right corner of Wabbajack.

3. Press the download arrow on the Vagabond UI card and wait for it to download.

4. Set the `Modlist Installation Location` to a folder such as `C:\Vagabond`. 
   > **DO NOT** set the folder to Program Files, User protected folders (such as Desktop, Documents, Downloads, etc.), or in your Skyrim's Steam folder.

5. The `Resource Download Location` line should fill out automatically after you set your `Modlist Installation Location`. 
   > The `Resource Download Location` does not need to be on an SSD, but it makes installing faster. You can set this location to a folder on an HDD for the sake of saving space.

6. Press the play arrow to begin the installation.

7. If the installation is successful, then rejoice and move onto the [Post Installation](#post-installation) section. If the installation is unsuccessful, refer to the [Problematic Files](#problematic-files) section and tips below or join the [discord server](https://discord.gg/WakingDreams) for support.

#### Problematic Files

Wabbajack can sometimes have trouble downloading mods hosted on sites other than Nexus. Because of this, many problematic files are listed below for your convienence. 

You will need to **manually download** these files and place them in the `Resource Download Location` that is made in the [Downloading and Installing Vagabond](#downloading-and-installing-vagabond) section.

**Google Drive Links:**
- [Elden Ring - Great Spear.7z](https://drive.google.com/file/d/19muJYVcS_CwVOsQ9bQL_wWsYRz5W7BZI/edit)
- [EldenRing_LegendaryWeapons.7z](https://drive.google.com/u/0/uc?id=11T5k_CAlFMoN9uwWuyRhdRprV7pGHb7n&export=download)
- [High Poly Head](https://drive.google.com/u/0/uc?id=15_0njBUjHKidNnJPmLXEygzGVWsA3Zbq&export=download)
- [[Dint999] BDOR Hairs SSE 0.15.7z](https://drive.google.com/u/0/uc?id=1vWIbrO7nHgW27HbjXBxMjuM3sJDitAF9&export=download)
- [[Dint999] HairPack02 SSE 1.11 (base).7z](https://drive.google.com/u/0/uc?id=1Ts0sQz3hDxhCeS_LUnXJQFuws_qbw9YQ&export=download)
- [[Dint999] FacePartMod (SSE) v0.6b.7z](https://drive.google.com/u/0/uc?id=1RQl8ki73fgLnzBZn6EWjneuW4Dk8TUO_&export=download)
- [[full_inu] Armor Pack 02 SSE.7z](https://drive.google.com/u/0/uc?id=12Siwo7JsLw03mJBqXrhHkKOcqPmGPX9k&export=download)
- [Real Wheat Fields of Skyrim](https://drive.google.com/uc?id=1aA15AVXDubSoizOnLeNm19TsnbvtpRZn&export=download)
- [Bloodstorm ENG](https://drive.google.com/uc?id=1wu9hwP_7QJC9tWxLwR8QU41txry5u9vA&export=download)
- [MCO Sprint Attack Stamina Fix](https://drive.google.com/uc?id=1qY8Xe8LAF63m3UVJM58xVj1TOTd3uR-l&export=download)
- [Olivier Kenjutsu Great Sword MCO](https://drive.google.com/uc?id=1Idn2Y-_dTCoRtUrohb0zNS3Nea2CfheY&export=download)
- [Olivier Kenjutsu Sword MCO](https://drive.google.com/uc?id=1DZMKj4B8FUeeAmhv7j3wA6yFQ2kg8w2w&export=download)

**Mega Links:**
- [Mod Organizer 2.4.5 Alpha 3](https://mega.nz/file/EmxzyLLb#0y6vxJ6iy0QRWNn2wTXV56CMkhyfAF8MunZ_w1RfeKE)


**Modding Guild Links:**

- [ElderSouls-The-Collection-v0.9-SE-(AMR).7z](https://modding-guild.com/archive/ElderSouls-The-Collection-v0.9-SE-(AMR).7z)
- [Valkyrie+Sword&Shield+v0.1.3.zip](https://modding-guild.com/archive/Valkyrie-Sword-Shield-v0.1.3.zip)
- [White+Fang+Dagger+v1.zip](https://modding-guild.com/archive/White-Fang-Dagger-v1.zip)

**Patreon Links:**

- [ADXP I MCO Nioh Dai-Katana (0.902) WIP.rar](https://www.patreon.com/file?h=76242640&i=12606554)
- [Elden Ring - Commander's Standard.7z](https://www.patreon.com/file?h=73960863&i=12153333)
- [Eskyrim MCO Installer 1.2.7z](https://www.patreon.com/file?h=68233071&i=11449877)
- [MCO Dual Axe Normal and Power Attacks.7z](https://www.patreon.com/file?h=68914571&i=11564092)
- [Miquellan Knight's Sword.7z](https://www.patreon.com/file?h=68558518&i=11200671)
- [Nagakiba.7z](https://www.patreon.com/file?h=68764133&i=11164539)
- [SC_HorseReplacer.7z](https://www.patreon.com/file?h=35289631&i=5312963)
- [SC_HorseReplacer_SSE(overwrites LE folder).7z](https://www.patreon.com/file?h=35289631&i=5428357)
- [Wo Long - Azure Dragon Crescent Glaive.7z](https://www.patreon.com/file?h=80323534&i=13464512)
- [d3dcompiler_43.zip](https://www.patreon.com/file?h=82920846&i=14179396)

### Problems with Installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download **X**:
  - Big files can fail to download due to connection issues or website issues. You can either run Wabbajack again or download the missing file manually. If you decide to manually download the file, make sure to place the file(s) inside the folder you set as the `Resource Download Location` in the [Downloading and Installing Vagabond](#downloading-and-installing-vagabond) section.

- **X** is not a whitelisted download:

  - This may happen when I update the modlist. Please check if there is a new update or wait until you see a release ping on the discord server.

- Wabbajack could not find my game folder:

  - Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
  - Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

- Unable to download `Data_ccXXXXX - *.bsa` or `*.esp`:
  - This error means Wabbajack is unable to hash your Creation Club Content. If you have followed the steps outlined under [Pre-Installation](#installing-creation-club-content), you are not on a pirated copy of the game, and have verified your steam files, then it is very likely that Bethesda has messed up the hashing for these files. If this is the case, please wait for an update ping on the discord server before continuing to download the list.

- Unable to download `Skyrim_Default.ini`:
  - This error means you failed to follow the readme. Go back to the [game language](#game-language) section and set your game language to English.

## Post-Installation

### ⚠ Verify Install ⚠

**THIS STEP IS MANDATORY.**

Due to size of the list, the chances of Wabbajack causing a corrupted installation is higher than usual. This can cause random crashes or issues that are not reproducible on the modlist author's end.

Please follow the steps in [this guide](https://github.com/Oghma-Infinium/Modding-Guides/blob/main/tutorials/Verifying%20your%20Modlist%20Install.md) right after your install is done to verify your Vagabond install does not have any errors. If you receive errors in the command prompt window after doing the steps in the guide *successfully*, delete the `mods` folder inside your `Vagabond` folder and rerun the Wabbajack installer for Vagabond again.

If you have any questions or issues doing this step, feel free to stop by the [discord server](https://discord.gg/WakingDreams) for help.

### Antivirus Exceptions

Generally speaking, using solely Windows Defender as your antivirus is advised as it is a solid antivirus software that will have minimal interference with the game.

Antivirus programs can be notorious for false flagging MO2's VFS (Virtual File Staging) as problematic, causing crashes or other issues. Antivirus programs like BitDefender, Norton, and Webroot are especially aggressive and you will very likely need to fully remove them from your PC in order to actually launch the game through MO2.

If you use Windows Defender, it is advised that you set up an exception for the modlist. To do this, follow these steps:

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

### Controller Keybinds

![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/controlmap3.png)

**Note:** Toggle POV button bind is disabled by default. Can be enabled with a mod in the optionals section of MO2.

## Playing the List

**Before you start playing the game, I suggest reading over the [Configuration page](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md) and the [FAQ page](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/FAQ.md) for the list.**

### Starting the Game

  Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it.

 1. Click the button that says `Run` next to the `Vagabond` executable in the top right of MO2.
      > The game may take 5-10 minutes to load on your first launch due to how big the list is. Please be patient and **DO NOT** click unlock on the MO2 pop-up.
 2. Once the game loads, start a new game. You will now spawn in a small room with a door in front for you.
 3. **(Optional)** Refer to MCM options here at the [Configuration page](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md).
 4. Press enter on your keyboard to create your character. The game will open Racemenu where you can customize your character.
 5. After you're done with the character creation you'll be presented with a message box. Choose continue to start your journey. Other messages boxes may pop up, just press `Ok` on those.

## Updating the modlist

Versioning for the list will adhere to the following format: `MAJOR.MINOR.PATCH`.

- `MAJOR`: Any release with a number change here will be considered a major update as at least 1 area of the list was massively overhauled. These updates with **NEVER** be save safe.
- `MINOR`: Any release with a number change here will be considered a minor update, these updates will usually not be save safe, unless otherwise specified.
- `PATCH`: Any release with a number change here will be considered a patch, these updates should be save safe and will be used primarily for bugfixes.
- In some rare cases you may see a fourth slot be used, which I will refer to as `HOTFIX`. These list "updates" will be used if the list needs to be recompiled for any reason. There will be no changes in these "updates" as they are purely for maintenance.
  
Before updating, please check the [changelog](https://github.com/Oghma-Infinium/Vagabond/blob/main/CHANGELOG.md) and back up your saves. The changelog will state if you may need to start a new game after certain updates.

Updating is like installing the list. Simply grab the latest version from Nexus, make sure your paths are the same as the ones you picked in [Downloading and Installing Vagabond](#downloading-and-installing-vagabond), and tick the `Overwrite Installation` button.
> **Note**: Any mods you have added will be deleted and *any* changes to the files in the list will be reset when updating. To make sure that Wabbajack does not delete your added mods upon updating, prefix your mods with `[NoDelete]`.

## Removing the Modlist

Simply delete the Vagabond folder. Congratulations, you have uninstalled Vagabond.

## Contact

**PLEASE DO NOT DM ME ON DISCORD!**

If you have an issue with the list, please join the [Waking Dreams](https://discord.gg/wakingdreams) discord server for support.

## Credits and Thanks

- *YOU* for reading this.
- [Phoenix](https://github.com/foreverphoenix) for making [Aurora](https://www.nexusmods.com/skyrimspecialedition/mods/89805), which was used as the visual base for the list.
- [aljo](https://ko-fi.com/aljoxo), [Bingus](https://ko-fi.com/beangas), Fate and the rest of the Waking Dreams server for helping me with the list.
- [ElminsterAU](https://www.patreon.com/ElminsterAU) and the xEdit team for SSEEdit.
- Noggog for Mutagen and Synthesis.
- Halgari and the WJ Team for this amazing platform.
- [Cosmofujia](https://www.patreon.com/fujiacosmo) for a significant amount of high quality Weapon Models.
