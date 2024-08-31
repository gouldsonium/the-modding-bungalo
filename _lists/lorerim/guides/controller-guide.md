---
layout: default
title: Controller Guide
parent: Guides
grand_parent: Lorerim
nav_order: 2
---
# Controller Set Up and Installation Guide
###### By theDudeStandard
A controller mapping mod primarily intended for Biggie Boss's LoreRim.
Requires the Steam Controller Mapping the link is on the Files download details.
Maps controller for TKDodge, One-Click Power Attack, Bow Rapid Combo, Wheeler, Stances, Simple Horses, Nether Follower Framework, Helmet Toggle, Bestia
## Step 1: Delete or Deactivate `ControlMap_Custom`

- **In LoreRim:**  
  Under the "Controller Support - MAKE SURE TO DISABLE KEYBOARD MAP" separator:
  - Deactivate the `"LoreRim - Keyboard Map (Disable for Controller Support)"` mod.
  - Activate `"Controller Map - VISIT NEXUS PAGE FOR MORE TIPS"`.

- **In Other Mod Lists:**  
  - Install and activate the Controller Map mod.
  - Search for `ControlMap_Custom` and delete all files found.

## Step 2: Apply Steam Controller Layout

- Paste the link in your browser (found in the download details):  
  `steam://controllerconfig/489830/3306747634`
- Select "Open Steam" & "Apply Layout" (controller must be on).

## Step 3: Download and Activate in MO2

- **Load Order:** Last active mod.

## Step 4: Button Mapping & Button Swapping

- Refer to `Button Mapping.txt` for more details.

## Step 5: Mapping Taunt In-Game

- In the `Taunt / Remote Int MCM Menu`, map Taunt to the `N` key.

## Available Button Swaps

To swap button configurations:
1. In the Mod Folder: `Controller LoreRim 2.0\interface\controls\pc`
2. Delete the file named `Controlmap`.
3. Copy the `Controlmap` file you want to use.
4. Rename it to `Controlmap`.

### Options Available:
1. `controlmap` (L3=Dodge+Sprint & Y=Jump) [default]
2. `controlmap` (L3=Dodge+Sprint & A=Jump)
3. `controlmap` (B=Dodge+Sprint & A=Jump)
4. `controlmap` (B=Dodge+Sprint & Y=Jump)

## Changing the Configuration to Match Your Playstyle

**Recommendation:** Use Skyrim Control Mapper to edit the `ControlMap.ini` file.  
- Map to the location of the file in your mod folder.
- The SHIFT mapping is set to `LB`. If you decide to switch the SHIFT button, you will need to remap that button in every line of the `.ini` file and the Steam Mapping.
  - *(Example: If you switch to `RB`, you will need to map SHOUT to `LB` in `ControlMap.ini` and edit the Steam mapping to use `RB` as the Chord Button for `LB`, `RB`, `LT`, `RT`.)*

**Credit**  
Thanks to the mod authors for their awesome mods. I've included their `.ini` files to modify the key mapping. **(DO NOT ASK THEM QUESTIONS)**
