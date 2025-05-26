---
layout: default
title: Read Me
parent: CSVP
nav_order: 1
---
# CSVP - Colloquy's Skyrim Vanilla Plus
Wabbajack Modlist Installer by **TheConversation**.

![Image]({{ site.baseurl }}/assets/csvp/logo.png)

<table style="border: none;">
<tr>
<td><a href="https://www.nexusmods.com/skyrimspecialedition/mods/135701">Nexus Page</a></td>
<td align="center">
  <a href="https://github.com/wabbajack-tools/wabbajack/releases">
    <img alt="Wabbajack" src="/assets/wabbajack.png" width="64px" >
  </a>
</td>	
<td><a href="https://loadorderlibrary.com/lists/csvp-colloquy-s-skyrim-vanilla-plus-a-ngvo-fork-2">Load Order Library</a></td>
<td><a href="https://loadorderlibrary.com/lists/csvp-performance">Load Order Library (Performance)</a></td>
<td align="center"><a href="https://discord.gg/Tb5ETzBYjd"><img alt="Discord" src="https://cdn.logojoy.com/wp-content/uploads/20210422095037/discord-mascot.png" width="64px" ></a></td>
</tr>
</table>

## Preamble

Colloquy's Skyrim Vanilla Plus is a modlist based on the visuals offered by 'Next Generation Visual Overhaul' from Biggie_Boss.  This is my take on his baseline, it is not a one-to-one baseline as there were quite a few things changed visually to my personal tastes. This list will require a fresh install of Skyrim: Anniversary Edition, and Wabbajack Installer (Please see the Read Me for Spec Recommendations and Space Requirements). It is intended as a packaged Vanilla Plus experience that can be played immediately with minimal effort.

## System Requirements

### Disclaimer

Owing to the need to clean master files and certain errors with Wabbajack, CSVP only supports **English Steam** versions of Skyrim Special Edition. **GOG and other Languages are not supported**.

{: .warning}
**CSVP REQUIRES YOUR SKYRIM VERSION TO BE UPDATED TO 1.6.1170 AND THIS IS THE GAME VERSION THAT THE MODLIST RUNS ON** 

### Recommended System Requirements

CSVP requires a mid-tier modern system to run to its fullest potential. The recommended specs given below are based on utilizing the ENB in the list. For community shaders, you can subtract a little bit from them. Users have reported being able to run on hardware slightly lower than this, however your mileage may vary.

| Component    | Recommended for Main | 
|:------------:|:-------------:|
| CPU | 12th Gen i5 Processor (Ryzen 7) or Higher
| Ram | 16GB 
| GPU | 30 Series GPU (RX 6000 series) with 12GB VRAM

| Component    | Recommended for Performance | 
|:------------:|:-------------:|
| CPU | 10th Gen i5 Processor (Ryzen 5) or Higher
| Ram | 16GB 
| GPU | 20 Series GPU (VEGA series) with 8GB VRAM

| Profile | Download Size  | Install Size | Total | Count | 
|:-------:|:--------------:|:------------:|:-----:|:------|
| Main    | ~135GB         | ~180GB       |~315GB | 1727 Mods, 1086  Plugins, 113 ESPs
| PERF    | ~135GB         | ~185GB       |~320GB | 1708 Mods, 1019 Plugins, 113 ESPs

Only, Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**. Your windows version **must be 21H2 or newer** to run both Wabbajack and CSVP.

Running the list from Hard Disk Drives or external drives is **STRONGLY ADVISED AGAINST**. A lot of content is swapped at game run time and, as a result, fast storage and RAM are needed.

----------------------------------------------------

{: .important}
>**Message from Modlist Author**
>
>This isn't an *"ongoing project"* or anything, it is simply my personal Modlist that I wanted to make accessible for the people close to me.
>
>That being said please don't expect the work of an expert, I am only a passionate fan. This list was built to be easy as possible to configure, you're at liberty to do so as you please.

----------------------------------------------------

## Installation

Installing CSVP is relatively easy and, if you have Nexus Premium, will be a simple waiting game.

### Pre-Installation

Prior to installing, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-8.0.5-windows-x64-installer)
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
6. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
7. Launch the game to the main menu and allow it to download the creation club addon files. **DO NOT VERIFY YOUR GAME FILES**
8. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.

----------------------------------------------------

## Wabbajack Installation
### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

{: .important}
**NOTE**: CSVP will **always** require the latest version of Wabbajack.

----------------------------------------------------

### Downloading and Installing CSVP
Downloading and installing can take a while depending on your internet connection and computer. To install, complete the following steps:

1. Open Wabbajack and click on Install from Disk.
2. Select the CSVP Wabbajack File, Press the download button and wait for it to download.
3. Set the installation folder to be somewhere like C:\CSVP. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

----------------------------------------------------

### Problems with installation
It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below. As a general rule of thumb; if a browser window pops up on failure you are likely missing files from Skyrim itself, if no browser pops up on failure it is most likely a Wabbajack issue and rerunning will solve it, and if a system error pops up on failure it is most likely AV related (Windows Defender counts too). Ensure you followed all Pre-Installation steps correctly.

### Could not download x:
Big files can fail to download due to connection issues. You can either run Wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
Make sure you have downloaded all the Paid AE update content!
Ensure you read and followed the Pre-Installation instructions correctly.

### x is not a whitelisted download:
This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

### Wabbajack could not find my game folder:
Either buy the game or go back to the Pre-Installation steps.

### Antivirus reports a virus:
You did not follow the steps in Pre-Installation. Go back and follow it.
If you have followed it then you can fix this by adding an exclusion for Mod Organizer in Windows Defender.

----------------------------------------------------

## Post-Installation

### Stock Game & Root Builder
CSVP utilizes a Wabbajack technology called Stock Game. What this essentially does is create a copy of your Skyrim installation within the installation location of the list. This enables greater compatibility with other mod-lists.

CSVP also utilizes Root Builder alongside Stock Game to enable easier management of hooks such as ENB, Reshade and Engine Fixes.

**NOTE:** Screenshots save to CSVP/overwrite.

----------------------------------------------------

## Starting up the list:
Open the installation folder and double-click on the program called ModOrganizer.exe.

{: .warning}
>**Warning**
>
>The first time you open Mod Organizer 2 the CC Files will not be in their Separator. In the left panel, place them in the "CORE FILES" Separator (above the 'Cleaned Plugins' Mod so it can overwrite them), this is optional but will look cleaner.

Make sure the dropdown box on the right is set to 'CSVP - A NGVO Fork' and press the Run button.

----------------------------------------------------

### In-game MCM options:
CSVP should have no required MCM options to be selected beyond the final steps above; if that is incorrect please let me know and I will fix it/post settings for the Mod in question.

You are welcome to change any/all others to achieve your desired setup.

----------------------------------------------------

## Known Bugs/Crashes:
If you are using an AMD GPU, you need to disable DLAA and enable TAA in the SkyrimPrefs.ini located in the profile folder. Otherwise, you WILL crash. You can then enable 'TAA Sharpen' for better visuals.
**FOR NVIDIA USERS if you are having shimmering edge issues with foliage, turn TAA on with DLAA but dont enable TAA Sharpen.

Dying and then reloading CAN cause crashes with Dyndolod DLL NG. The alternative is to disable Dyndolod DLL NG and re-run Dyndolod. This will enable Dyndolod via papyrus scripts which resolves this issue but is heavier FPS-wise and has worse lods.

----------------------------------------------------

## Post-Game (OPTIONAL STEPS)
Closing the game after loading up for the first time, you will have a notification in the top right regarding files in your Overwrite. SKSE, ShaderCache, and MCM related files can be dragged to the 'SKSE & MCM Output' Mod in the Outputs Separator. KiLoader related files can be dragged to the 'KiLoader Output' Mod in the Outputs Separator.

The folder marked 'textures' in your Overwrite folder is generated by PhotoMode, it will always regenerate after every session so deleting it is completely optional and would only be for the sake of having zero notifications.

----------------------------------------------------

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

----------------------------------------------------

## Credits:
- **YOU** for reading this.
- Biggie_Boss for NGVO.
- JaySerpa for GTS.
- Halgari and everyone on the WJ Team - Wabbajack is awesome and so are you.
- All of the amazing mod authors whose work made this modlist possible.
- Everyone in the Modding Bungalo Discord - You all inspire me.
