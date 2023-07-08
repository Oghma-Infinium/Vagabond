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
    - [Game Folder](#game-folder)
    - [Antivirus Exceptions](#antivirus-exceptions)
    - [Controller and Gamepad Setup](#controller-and-gamepad-setup)
  - [Playing the List](#playing-the-list)
    - [Starting the Game](#starting-the-game)
    - [In-Game MCM options](#in-game-mcm-options)
  - [Updating the modlist](#updating-the-modlist)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
      - [Performance INI Options](#performance-ini-options)
      - [BethINI](#bethini)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact](#contact)
  - [Credits and Thanks](#credits-and-thanks)

## Introduction

Vagabond is a Skyrim modlist for Anniversary Edition with focus on visuals, modernized combat, and Legacy of the Dragonborn. In addition, Enairim suite is chosen for most gameplay overhauls, including Vokriinator Black for perks. Wide array of monster, weapon, armor and location overhauls are included to make the world more diverse.

The full modlist can be viewed [here](https://loadorderlibrary.com/lists/vagabond).

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

### System Requirements

>  Please note these specs are the best idea of a baseline that I can provide at the current moment, based on feedback I have gotten from testers and my own experiences. In the future this will be updated depending on feedback received.


| Spec Category | My Specs (1440p) | Recommended (1080p) |
|     :---:    |     :---:     |     :---:     
| **CPU**   | R7 5800X |  R7 3700x / i5 10600k |
| **Video Card**    | 3080 | 3060 Ti / 2070 / 6700 XT |
| **Ram**    | 32gb (2x16) | 16gb (2x16) |
| **Storage**    | 970 EVO NVMe | SATA SSD |

Downloads: ~260 GB  
Install: ~450 GB  
Temp Files: ~30 GB (on OS drive)  
**TOTAL:** ~740 GB  

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
- List GDrive/MEGA Downloads

Sometimes the SkyrimGuild website also runs into issues so I suggest downloading these in advanced as well.
- [Attack+MCODXP+v1.6.0.5.zip](https://www.skyrim-guild.com/s/Attack-MCODXP-v1605.zip)
- List SkyrimGuild Downloads

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
 2. Once the game loads start a new game.
 3. The game will open in Racemenu where you can customize your character. Guide for adding presets will be included later.
 4. After you're done with the character creation you'll be presented with series of message boxes that you can use to configure the start of your journey.
 5. After picking your options, your playthrough will start just outside the Helgen Keep cave with the main quest continuing as normal.
 6. You may adjust MCM settings to your liking, the default settings are for my preferred experience.

### In-Game MCM options

 - **Smoothcam**: Try out various presets included if you don't like the default camera.

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

### Tweaking the Game Settings

#### Performance INI Options

Here are recommended ini tweaks that you can make in order to potentially improve performance without messing up the visuals of the list and/or ENB. These files can be found at `[Path to Modlist]\profiles\YLIK WRITE PROFILE NAME HERE`.

**Skyrim.ini**  
>[Display]  
fSAOIntensity=15  
fSAOExpFactor=0.220  
fSAORadius=800.0000  
fSAOBias=0.5000  
fSAOValueDiffFactor=0.3000

#### BethINI

Before running BethINI please make sure that your paths are correctly set. I also suggest backing up the original `.ini` files just in case. 

 - **Game**: `Skyrim Special Edition`
 - **Game Path**: `[Path to Modlist]\Stock Game`
   - example: `F:\Vagabond\Stock Game`
 - **Mod Organizer**: `[Path to Modlist]` 
   - example: `F:\Vagabond`
 - **INI Path**: `Mod Organizer > YLIK WRITE PROFILE NAME HERE`

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

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
