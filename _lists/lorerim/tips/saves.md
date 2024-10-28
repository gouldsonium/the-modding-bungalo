---
layout: default
title: Safe Saving
parent: Tips
grand_parent: Lorerim
nav_order: 4
---
# Safe Saving & Loading
###### By shallowgreen

Big modlists don't play nice with saving and loading, especially frequent reloading. To avoid players breaking their saves, Lorerim uses a respawn system. When you die, you respawn where you last slept. If you have to reload a save, best do so by quitting out and re-launching Lorerim.

## Safe saving, loading & respawning in Lorerim:

Lorerim uses a respawn system which if you die, will simply respawn you where you last slept. 
You'll want to use this instead of reloading while you're playing, since reloading while you're already playing can cause issues - things like suspended scripts not firing up correctly. 
If this happens when you reload, and you then save on top of it, there's a chance you bake this issue into your save and carry it forward - which can lead to instability, more frequent crashing and eventually, an entirely unloadable, corrupted save. 

If you want to load a save, only do so by quitting out and re-launching Lorerim first.

**Things you should avoid when saving:**
- Don't save during combat
- Don't save during heavily scripted sequences, such as from some quests
- Don't save immediatly after entering a cell (give it a few seconds)
- Don't save in quick succession, give it at least a minute or two
- Don't load from an ongoing session, as described above

## Camping
Handily, general vendors sell camping supplies - you can use these straight from your inventory to set up a camp, complete with a campfire, bed, storage, and on higher-tier camps, even crafting stations. Whenever you're about to do something foolish, plop down your campsite and take a quick nap to set your respawn location. 

The storage between multiple campsites is not shared, and when packing your campsite back up, anything in its storage will be dumped into your inventory.

Two notes: 
- There are some no-respawn zones in the game, if you encounter one of those you'll get a popup, saying "You will surely perish if you are defeated while in this location". This is simply a failsafe to prevent you from respawning outside of locations you're not supposed to be able to leave (i.e. locked in) or because a scripted event that needs you to stick around needs to happen.
- Players cannot respawn while transformed into a werewolf or vampire lord. If you die while transformed, the game will simply boot you to the main menu, or straight up crash - this is intended, as respawning while transformed causes issues.