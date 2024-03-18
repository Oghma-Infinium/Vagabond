![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/Vagabond%20Banner%20PNG.png)

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

**[Modlist Support](#contact)**

**⚠ WARNINGS ⚠:**
- **You must update Skyrim Special Edition to latest version on Steam to install this list. DO NOT DOWNGRADE YOUR GAME TO INSTALL THIS LIST!**
- **Modifying the list in any way voids offical support for the modlist.**


# Contents

- [Contents](#contents)
  - [Introduction](#introduction)
    - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Prerequisites](#prerequisites)
      - [Pagefile and Crash Prevention](#pagefile-and-crash-prevention)
      - [Setting Shader Cache Size (NVIDIA Graphics Cards Only)](#setting-shader-cache-size-nvidia-graphics-cards-only)
      - [Installing Creation Club Content](#installing-creation-club-content)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing Vagabond](#downloading-and-installing-vagabond)
      - [Problematic Files](#problematic-files)
    - [Problems with Installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Antivirus Exceptions](#antivirus-exceptions)
    - [Keyboard Keybinds](#keyboard-keybinds)
    - [Controller Keybinds](#controller-keybinds)
  - [Playing the List](#playing-the-list)
    - [Starting the Game](#starting-the-game)
  - [Updating the Modlist](#updating-the-modlist)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact](#contact)
  - [Credits and Thanks](#credits-and-thanks)

## Introduction

Vagabond is a modlist for Skyrim Special Edition with a focus on visuals, modern combat, and Legacy of the Dragonborn. EnaiRim suite is chosen for most gameplay overhauls, including Vokriinator Black for perks. A wide array of monster, weapon, armor, spell and location overhauls are included to make the world more diverse. This list also has full seasons support, including unfreezing of snowy areas during Summer.

If you're curious about the specific mods in the list, the full modlist can be viewed [here](https://loadorderlibrary.com/lists/vagabond).

**NOTE:** Making ***ANY*** changes, — including editing INIs or MCMs —to the modlist, adding mods, removing mods, counts as modification and thus voids official support. Only changes explicitly stated in the [Config Doc](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md) are supported. There is separate channel in Discord for discussing modifications to Vagabond.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

### System Requirements

**DISCLAIMERS:**
- Vagabond only supports English Steam versions of Skyrim SE. GOG and other languages are not supported.
- HDD and external SSD installs are absolutely not supported.
- Any remote PC / desktop services or apps are not supported. (Including Steam Link)
- Only Windows 10/11 operating systems are supported. Windows LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK.**
- At least 16GB of GPU VRAM minimum is recommended for the list (1080p) or 10GB for performance profile, otherwise you'll experience frequent stutters in exteriors. Higher resolutions may require even more.
- Perfromance profile can be enabled post-installation. Explained in [config](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md#performance-profile).

> Please note these specs are the best idea of a baseline that I can provide at the current moment, based on feedback I have gotten from testers and my own experiences. In the future this will be updated depending on feedback received.

| Spec Category | Default (1080p) | Performance (1080p) | My specs (2160p) |
|     :---:    |      :---:    |      :---:     |      :---:     |
| **CPU**   | R7 5800X3D / i7 12700k | R7 5700X / i5 12600 | R7 7800X3D |
| **Video Card**    |  RTX 4070ti super / RX 7800-XT  |  RTX 3080 / RX 6800  |  RTX 4090  |
| **Ram**    | 32GB DDR4/5 | 32GB DDR4/5 | 32GB DDR5 6GHz |
| **Storage**    | SATA/NVME SSD | SATA/NVME SSD | Samsung 970 EVO Plus |
| **OS**    | Windows 10/11 | Windows 10/11 | Windows 10 |

Downloads: ~426 GB  
Install: ~467 GB  
Temp Files (OS drive): ~30 GB  
Temp Files (install drive): ~130 GB  
**TOTAL:** ~ 1053 GB  

 > Wabbajack requires around 160 GB of space for temporary and working files during the installation. The total size after installation is done is closer to 893 GB.

## Installation

**⚠ WARNINGS ⚠:**
- **You must update Skyrim Special Edition to latest version on Steam to install this list. DO NOT DOWNGRADE YOUR GAME TO INSTALL THIS LIST!**

If you are updating the modlist, you can safely skip to the [updating section](#updating-the-modlist).

### Pre-Installation

#### Prerequisites
Prior to installing Vagabond, please complete the following steps:

 1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe) & [.Net Runtime v6 Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).
 2. Reinstall Skyrim into a location that is not Program Files. Locations such as `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
 3. Disable the Steam Overlay: Right click on Skyrim SE in Steam and click on `Properties` > Untick the `Enable Steam Overlay while in-game` option
 4. Set your Skyrim language to English: Right click on your Skyrim in Steam > Click `Properties` > Click the drop down box next to `Language` > Set the language to English
 5. Remove or disable any 3rd party antiviruses such as Webroot or Bitdefender. These programs can cause issues with your Vagabond installation due to how MO2's Virtual File Staging works.
 6. (Soft Requirement) A Nexus Premium account is recommended. Without Premium, you will need to manually click the `Slow Download` button for each mod.

---

#### Pagefile and Crash Prevention

Larger Skyrim modlists require a significant amount of memory and running out of memory **will** result in crashes and other potential issues. 

Due to Vagabond's size and number of files required to be handled for the list, this step is **NOT** optional. **Regardless of how much RAM or VRAM you have, please do this step.**

 To set up your pagefile:

 1. Press **Win Key + R**
 2. Type *sysdm.cpl ,3* and hit **ENTER**
 3. Navigate to *Performance* and click the box "Settings..."
 4. Click the *Advanced* tab at the top
 5. Under *Virtual Memory* click the box "Change..."
 6. Uncheck *Automatically manage* if it is checked
 7. Select your disk drive, ideally your fastest solid state drive.  
  
    > This **can't** be a HDD or an external SSD.
 
 8. Click the **Custom size:** button
 9. In the box next to **Initial Size (MB)** type `40960`
 10. In the box next to **Maximum Size (MB)** type `40960`
 11. Click the *Set* button
 12. Click *OK*
 13. Click *Apply*
 14. Click *OK*
 15. Restart your computer in order for your new pagefile to take effect.

---

#### Setting Shader Cache Size (NVIDIA Graphics Cards Only)

 Additionally, if you have an NVIDIA GeForce Graphics Card, please do the following:

 1. Right-click on your desktop and select **NVIDIA Control Panel**
 2. Navigate and click on **Manage 3D settings**. It is the 2nd one to the top.
 3. Scroll down in Global Settings until you see **Shader Cache Size**
 4. Double Click **Driver Default** to the right of Shader Cache Size and select **10 GB**
 5. Click **Apply** in the bottom right hand corner.
 6. You may exit out of the application.
![](https://raw.githubusercontent.com/iAmMe27/Tahrovin/main/img/ShaderCache.png)

---

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, follow the steps below to install Wabbajack:

1. Create an empty folder named `Wabbajack` on the root of your drive, such as `C:\Wabbajack` for example. **DO NOT set the folder to Program Files, User protected folders (such as Desktop, Documents, Downloads, etc.), or in your Skyrim's Steam folder**.
   > The `Wabbajack` folder does not need to be on an SSD, but it makes installing faster. You can create a `Wabbajack` folder on an HDD instead for the sake of saving space.

2. Download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place the `Wabbajack.exe` file inside the Wabbajack folder you created in Step 1. **Do not** use older versions of Wabbajack unless instructed by staff.

3. Double-click the `Wabbajack.exe` file that is now inside your Wabbajack folder to set up the program.

---

#### Downloading and Installing Vagabond

Downloading and installing Vagabond can take a while depending on your internet connection, PC specs, and if you have Nexus Premium.

To install Vagabond, complete the following steps:

1. Open Wabbajack and click `Browse Modlists`

2. Press the download arrow on the Vagabond UI card and wait for it to download.

3. Set the `Modlist Installation Location` to a folder such as `C:\Vagabond`. 
   > **DO NOT** set the folder to Program Files, User protected folders (such as Desktop, Documents, Downloads, etc.), or in your Skyrim's Steam folder.

4. The `Resource Download Location` line should fill out automatically after you set your `Modlist Installation Location`. 
   > The `Resource Download Location` does not need to be on the same drive as your Modlist Installation Location. You can set this location to a folder on an HDD for the sake of saving space.

5. Press the play arrow to begin the installation.

6. If the installation is successful, then rejoice and move onto the [Post Installation](#post-installation) section. If the installation is unsuccessful, refer to the [Problematic Files](#problematic-files) section and tips below or check the [Contact](#contact) section for support.

---

#### Problematic Files

Wabbajack can sometimes have trouble downloading mods hosted on sites other than Nexus. Because of this, many problematic files are listed below for your convienence. 

You will need to **manually download** these files and place them in the `Resource Download Location` that is made in the [Downloading and Installing Vagabond](#downloading-and-installing-vagabond) section.

**Google Drive Links:**
- [Elden Ring - Great Spear.7z](https://drive.google.com/file/d/19muJYVcS_CwVOsQ9bQL_wWsYRz5W7BZI/edit)
- [EldenRing_LegendaryWeapons.7z](https://drive.google.com/u/0/uc?id=11T5k_CAlFMoN9uwWuyRhdRprV7pGHb7n&export=download)
- [High Poly Head](https://drive.google.com/u/0/uc?id=15_0njBUjHKidNnJPmLXEygzGVWsA3Zbq&export=download)
- [[Dint999] BDOR Hairs SSE 0.17.7z](https://drive.usercontent.google.com/download?id=1tpY3bDs-LR6rptf8oPUfraKs1CkxJJB3&export=download&authuser=0)
- [[Dint999] HairPack02 SSE 1.11 (base).7z](https://drive.google.com/u/0/uc?id=1Ts0sQz3hDxhCeS_LUnXJQFuws_qbw9YQ&export=download)
- [[Dint999] FacePartMod (SSE) v0.6b.7z](https://drive.google.com/u/0/uc?id=1RQl8ki73fgLnzBZn6EWjneuW4Dk8TUO_&export=download)
- [[full_inu] Armor Pack 02 SSE.7z](https://drive.google.com/u/0/uc?id=12Siwo7JsLw03mJBqXrhHkKOcqPmGPX9k&export=download)
- [Real Wheat Fields of Skyrim](https://drive.google.com/uc?id=1aA15AVXDubSoizOnLeNm19TsnbvtpRZn&export=download)
- [Bloodstorm ENG](https://drive.google.com/uc?id=1wu9hwP_7QJC9tWxLwR8QU41txry5u9vA&export=download)
- [MCO Sprint Attack Stamina Fix](https://drive.google.com/uc?id=1qY8Xe8LAF63m3UVJM58xVj1TOTd3uR-l&export=download)
- [Olivier Kenjutsu Great Sword MCO](https://drive.google.com/uc?id=1Idn2Y-_dTCoRtUrohb0zNS3Nea2CfheY&export=download)
- [Olivier Kenjutsu Sword MCO](https://drive.google.com/uc?id=1DZMKj4B8FUeeAmhv7j3wA6yFQ2kg8w2w&export=download)
- [[dint999] BDOr Winter Mountain Guardian Spirit](https://drive.google.com/file/d/1siyc644OSI0Lz8PlM9lo3Gxf_VxQLlN5/view)
- [[SE] BDO Herawen Xing CBBE 3BA SMP SE](https://drive.google.com/file/d/1rXV6ftgxGnvvo6_RfAnpchAezr4s3Y48/view)
- [[SE] Kirax_BDO DK 0172 SMP 3BA](https://drive.google.com/file/d/1TkeHDdN48ybtTeRH5zpE9_cjKCGAgiHq/view)
- [[SE] Kirax BDO Rosa Le Dessous SMP 3BA](https://drive.google.com/file/d/1w8FYON11jWnOY0J8yqaMxKUtEYuI6TdA/view)
- [[SE] DM BDOR Hamshin](https://drive.google.com/file/d/1huAumy3LIObVxpDaw2JdA9_KNQICmSiE/view)
- [[SE] BDOR Checkmate 3BA fix](https://drive.google.com/file/d/1iy9FT2kf8vq2g0aTOuFtlLNKiyUepfq9/view)
- [[SE] DM BDOR Caroxya](https://drive.google.com/file/d/11Ix_VTvmZjxMxz0sHpgj1WWtJgH3dozI/view)
- [[SE] DM BDOR Danharum](https://drive.google.com/file/d/1wUpZayp2hDMbd4303-SYZLfLUqJdwQsK/view)
- [[SE] DM BDOR Mueburus](https://drive.google.com/file/d/1NL26SeJQClfAoq-4NqrcRAsrV3oi2wNb/view)
- [[SE] DM BDOR Adamas](https://drive.google.com/file/d/1bBhqwH969t1UBVAJVtOog9k2uKJQ-hjY/view)
- [[SE] DM BDOR Aquila](https://drive.google.com/file/d/1AfWT6nlJ3FGTRXSbPKGrpD1QjYipBPTs/view)
- [DM BDOR Dobart](https://drive.google.com/file/d/1Q2lSwBX4fRFWeP5tE5eSaSibfXgMPn0G/view)
- [[SE] DM BDOR Nova Taritas](https://drive.google.com/file/d/1_OGjX0QK7tgzK7CDRPEY0A7Dswzln1Av/view)
- [[SE] Kirax BDO Cavaro SMP 3BA](https://drive.google.com/file/d/1qDN1OymReXzS52ZidrD4JywEgnpus-D5/view)
- [[SE] Kirax BDO DK Ataraxia SMP 3BA](https://drive.google.com/file/d/1qBpFZmOIp6B_JmSXl7-FB4kLDeDeJxAf/view)
- [[SE] Kirax BDO Yinixtra SMP 3BA](https://drive.google.com/file/d/1_rAtCZFiffF-QaCCZ0hz6Svw5mRfcoex/view)
- [[SE] DM BDOR Sephia](https://drive.google.com/file/d/1qfS_8ccC_C6Qq88toPffLMrQv0kIpmmh/view)

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

---

### Problems with Installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Unable to download `Skyrim_Default.ini`:
  - This error means you failed to follow the readme. Go back to the [Prerequisites](#prerequisites) section and set your game language to English.

- Could not download **X**:
  - Big files can fail to download due to connection issues or website issues. You can either run Wabbajack again or download the missing file manually. If you decide to manually download the file, make sure to place the file(s) inside the folder you set as the `Resource Download Location` in the [Downloading and Installing Vagabond](#downloading-and-installing-vagabond) section.

- **X** is not a whitelisted download:
  - This may happen when I update the modlist. Please check if there is a new update or wait until you see a release ping on the Discord server.

- Wabbajack could not find my game folder:
  - Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
  - Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

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

---

### Keyboard Keybinds
![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/keyboard-layout_Vagabond.jpg)

### Controller Keybinds

![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/controlmap3.png)

**NOTE: Some keybinds on both maps are outdated for the current version. These will be updated eventually.**
## Playing the List

**Before you start playing the game, I suggest reading over the [Configuration page](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md), the [FAQ page](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/FAQ.md) and the [Gameplay Guide](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/GAMEPLAY.md) for the list.**

### Starting the Game

  Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it.

 1. Click the button that says `Run` next to the `Vagabond` executable in the top right of MO2.
      > The game may take 5-10 minutes to load on your first launch due to how big the list is. Please be patient and **DO NOT** click unlock on the MO2 pop-up.
 2. Once the game loads, start a new game. You will now spawn in a small room with a door in front for you.
 3. **(Optional)** Refer to MCM options here at the [Configuration page](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md).
 4. Press enter on your keyboard to create your character. The game will open Racemenu where you can customize your character.
 5. After you're done with the character creation you'll be presented with a message box. Choose continue to start your journey. Other messages boxes may pop up, just press `Ok` on those.

## Updating the Modlist

Versioning for the list will adhere to the following format: `MAJOR.MINOR.PATCH`.

- `MAJOR`: Any release with a number change here will be considered a major update as at least 1 area of the list was massively overhauled. These updates with **NEVER** be save safe.
- `MINOR`: Any release with a number change here will be considered a minor update, these updates will usually not be save safe, unless otherwise specified.
- `PATCH`: Any release with a number change here will be considered a patch, these updates should be save safe and will be used primarily for bugfixes.
- In some rare cases you may see a fourth slot be used, which I will refer to as `HOTFIX`. These list "updates" will be used if the list needs to be recompiled for any reason. There will be no changes in these "updates" as they are purely for maintenance.
  
Before updating, please check the [changelog](https://github.com/Oghma-Infinium/Vagabond/blob/main/CHANGELOG.md) and back up your saves. The changelog will state if you may need to start a new game after certain updates.

Updating is like installing the list. Simply grab the latest version from Wabbajack UI, make sure your paths are the same as the ones you picked in [Downloading and Installing Vagabond](#downloading-and-installing-vagabond), and tick the `Overwrite Installation` button.
> **NOTE**: Any mods you have added will be deleted and *any* changes to the files in the list will be reset when updating. To make sure that Wabbajack does not delete your added mods upon updating, prefix your mods with `[NoDelete]`.

## Removing the Modlist

Simply delete the Vagabond folder. Congratulations, you have uninstalled Vagabond.

## Contact

**PLEASE DO NOT DM OR PING  ME ON DISCORD! (INCLUDING REPLY PINGS)**

You are **required** to read the [FAQ](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/FAQ.md), [Config](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/CONFIG.md), [Gameplay Guide](https://github.com/Oghma-Infinium/Vagabond/blob/main/Documentation/GAMEPLAY.md) and [Trello](https://trello.com/b/khix4egd/vagabond-bug-reports) before seeking support.

If you still have an issue with the list after reading the above docs, feel free to join the [Waking Dreams](https://discord.gg/wakingdreams) Discord server for support. **Only latest version of the list is supported.** Please be mindful of pings when asking for support and note that modified installations are **not supported**. **Modifying the list in any way voids offical support for the modlist.**

**If you encounter issues with an item/NPC/object or similar, please click the item in console and take a screenshot when submitting a bug report. Posting a screenshot of the issue without a console click will most likely be overlooked.**

## Credits and Thanks

- *YOU* for reading this.
- [Phoenix](https://github.com/foreverphoenix) for making [Aurora](https://www.nexusmods.com/skyrimspecialedition/mods/89805), which was used as the visual base for the list.
- [aljo](https://ko-fi.com/aljoxo), [Bingus](https://ko-fi.com/beangas), Fate and the rest of the Waking Dreams server for helping me with the list.
- [ElminsterAU](https://www.patreon.com/ElminsterAU) and the xEdit team for SSEEdit.
- Noggog for Mutagen and Synthesis.
- Halgari and the WJ Team for this amazing platform.
- [Cosmofujia](https://www.patreon.com/fujiacosmo) for a significant amount of high quality Weapon Models.
