---
layout: default
title: Installation
parent: Guides
grand_parent: A Painted World
nav_order: 1
---

# Installation
Need help installing the list? This guide will help

Current version is 0.3.2 and is available at the google drive link below. Total install size is ~72gb. Please consider trying it to help me find issues or things I may have overlooked and provide feedback on how the list plays. Having a focused list of things to work on is immensely helpful for development.

## Pre-installation Requirements: 
- The game and mod list must be installed outside of a Windows Protected folder on an internal SSD.
- Launch the game to the title screen and close it. Navigate to Documents\My Games\Oblivion and open RendererInfo.txt in a text editor. On the last line you should see:

```
Shader Package         : 19
```

If this does not say 19 for you, change it so that it does. Close and save the file, then right click it and select Properties. Make a checkmark on Read-only.
- Setup a manual page file (1.5x the size of your total RAM) https://www.tomshardware.com/news/how-to-manage-virtual-memory-pagefile-windows-10,36929.html
- Make sure your VC redist is up to date. https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022
- You may also be missing a codecs pack, this is important for audio to play correctly and can cause crashes if it is missing. Get the basic version from this link. https://www.codecguide.com/download_kl.htm
- Disable any Nvidia, Steam, or other overlays

If you neglect any of of these requirements then I will not entertain your reports.

## Installation Instructions: 
You will need a vanilla copy of Oblivion GOTY Deluxe edition from [Steam](https://store.steampowered.com/sub/1679/).

Download the wabbajack file here, run the Wabbajack.exe and select download from disk.

[Download Wabbajack File](https://drive.google.com/file/d/1tRgnz5mbyVS6mla-lGJybCYEGvxnsCMj/view){: .btn }

Then navigate to where you installed the .wabba file. Select a folder to install the list to (Modding\APW would be my suggestion).

Wait for the list to finish downloading and installing, then make sure your resolution in the Oblivion.ini located in APW\profiles matches your monitor resolution using the below settings:
```
iSize W=
iSize H=
```
If you have an AMD graphics card, ensure that bFullScreen is set to 0 as well or you will have a black screen on the main menu.

Check the Ultrawide Separator or Optional mods separator for mods you might want to enable/disable. Now you can click Run in the top right corner of mod organizer and the game will launch like normal.

## Common Failed Downloads
If you get a failed downloads error in wabbajack from these mods, please download from the links below and manually move them to the downloads folder of the modlist, then rerun wabbajack.

[Fire Retexture 1k 1.2](https://www.mediafire.com/download/ctd689d2etnlabw/fire+retexture+1k+1.2.rar)
