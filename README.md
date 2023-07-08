# Vagabond
A Skyrim modlist with focus on visuals, modernized combat and Legacy of the Dragonborn.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## :information_source: Preamble

**This list is currently in beta-testing state.**

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

You can take a look at the [load order library](https://loadorderlibrary.com/lists/vagabond) to see what the list contains.

## :computer: System Requirements

Vagabond only supports **English Steam** versions of Skyrim AE (Including the **paid AE upgrade**). **GOG and other Languages are not supported**.
Only, Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**.

- Need reports from users before I can determine system requirements for the list. 10GB of vram and 32GB of ram is recommended. You might get away with 8GB vram / 16Gb ram.

My specs (1440p 21x9, DLSS performance, 45-60 fps on most exterior areas):

- i9 9900K
- 32GB DDR4
- NVME M.2
- RTX 2080ti

Space required: Approx 452GB install + 262GB downloads (can delete after install) + 30GB working room for Wabbajack.

:warning: **NOTE**: AMD RX 580 and HDD installations are **not supported**. :warning:

Installing Vagabond is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### :clipboard: Pre-Installation

Prior to installing Vagabond, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
6. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
7. Start the game to the main menu in order to download all the creations.
8. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.

***

### :page_with_curl: Wabbajack Installation

#### :scroll: Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

:warning: **NOTE**: Vagabond will **always** require the latest version of Wabbajack **UNLESS IT IS SPECIFICALLY STATED HERE**. :warning:

#### :open_file_folder: Downloading and Installing Vagabond

Downloading and installing Vagabond can take a while depending on your internet connection and computer. To install Vagabond, complete the following steps.

1. Open Wabbajack and click on browse modlists. Check the tickbox that says `show unofficial`.
2. Press the download button on Vagabond and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Vagabond. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

***

##### :confused: Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
	- **Make sure you have downloaded all the creation club content!**

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
	- If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## :floppy_disk: Post-Installation

### :file_folder: Stock Game

Vagabond utilises a Wabbajack technology called Stock Game. What this essentially does is create a copy of your Skyrim installation within the installation location of the list. This enables greater compatability with other mod-lists.

***

### :telescope: ENB

Vagabond uses [NAT.ENB III - Natural and Atmospheric Tamriel ENB 3.1](https://www.nexusmods.com/skyrimspecialedition/mods/27141) for its weather mod - ENB combination and the full [Lux](https://www.nexusmods.com/skyrimspecialedition/mods/43158) suite for lighting improvements.

***

### :runner:  Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `Vagabond` and press the `Run` button.

### :bookmark: In-Game MCM options

Vagabond has no required MCM options to be selected, however you can load the smoothcam preset if you wish to do so.

- SmoothCam
	- Load Preset

You are welcome to change any others to achieve your desired setup.

## :chart_with_upwards_trend: Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## :put_litter_in_its_place: Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## :hearts: Credits and Thanks

- _YOU_ for reading this.
- Phoenix for making Aurora, which was used as visual base for the list.
- Aljo, Bingus and rest of the Waking Dreams server for helping me with the list.
- Noggog for Mutagen.
- Althro for the readme template which you're reading right now.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

## :telephone_receiver: Contact

Whilst I am available primarily on [Waking Dreams server](https://discord.gg/wakingdreams) DO NOT DM ME ON DISCORD.
