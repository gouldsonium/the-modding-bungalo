---
layout: default
title: Known Issues
parent: Tips
grand_parent: Lorerim
nav_order: 2
---
# Known Issues
There are some issues which may occur thanks to good old Skyrim jank. If you've ran into an issue be sure to check here before reporting it. Or better yet, read before you play the list to avoid running into the issue.
## General Issues

- **AMD Users:** You **WILL** crash if you don't disable DLAA. If you disable DLAA, make sure to enable TAA in `SkyrimPrefs.ini` located in the `profiles/default` (or `performance`) folder.

- **Reading a Book on Horseback:** This can cause camera issues. Saving and reloading the game fixes it.

- **Using Your Last Self-Made Potion/Poison While It's Binded in Wheeler:** This can cause crashes. Press "Home" and reset the wheeler to fix this.

- **Unarmed Stances:** These can cause a very faint noise in the background. Reloading fixes this, or you can turn down the magic effects slider.

- **Follower Issues:** Nether's Follower Framework is designed for vanilla followers. **Modded followers like Lucien and Inigo have their own framework and should NOT BE IMPORTED.** Importing them can cause issues.

- **Missives Bug:** Missives sometimes bugs out with gathering quests. It's recommended not to pick them up.

- **Souls Respawn Bug:** This will bug out if you become a vampire lord with Harkon. You can use `tcl` in the console to move into the next area.

- **Left-Handed Spear Issue:** The left-handed spear will appear on the hip in first person. This won't be fixed.

- **SPID Issue:** Sometimes enemies will carry multiple sets of armor/clothes.

- **Crash on Loading/Changing Cells:** This can sometimes happen randomly due to either DynDOLOD DLLs or Lux. Please only report if these are repeatable. You can minimize these by setting a page file, updating drivers, and getting prerequisites per GitHub.

- **Saints & Seducers Thoron Bug:** If Thoron won't die, click on him in the console, type `disable`, then type `markfordelete`, and finally type `setstage EC_SS_MQ102 89`.

## Vanilla Issues

- **Followers Resetting Inventories:** Sometimes followers can reset their inventories when they level. There's no known fix; it’s random, so don't get too attached to follower gear.

- **Word Walls Not Working:** Sometimes word walls don't do anything when you walk up to them. Just leave the cell and come back.

- **A Soul Divided Bug:** Sometimes this quest gets stuck. You'll have to either reload or complete the quest via console.

- **Valdar the Ghost Not in Valthume:** This is a vanilla (or possibly Requiem) issue. To fix, use the console command: `prid 8CE78`, then type `enable`.

- **Varona Still Alive in Reluctant Steward:** Sometimes Varona is still alive. You can kill her and progress the quest via console.

- **Mannequins Issue:** Mannequins won't equip helmets and can be used to duplicate armor.