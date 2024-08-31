---
layout: default
title: Stability & Performance
parent: Tips
grand_parent: Lorerim
nav_order: 3
---

# Lorerim Performance Optimization Guide

**Lorerim** is a heavy mod list with next-gen visuals but has been optimized for medium-spec users. Check out this guide to further improve performance.

## Profiles

- **Normal Profile:** Offers better performance than the Ultra profile. The main difference is the use of *Happy Little Trees* instead of *Nature of the Wild Lands* and the absence of grass LODs.

## CPU Affinity

**I RECOMMEND EVERYBODY SET THEIR CPU AFFINITY**

![Image]({{ site.baseurl }}/assets/lorerim/CPU-affinity.png)

## Page File

Setting a Page File **IS MANDATORY**. You can see how to do this [here](https://www.tomshardware.com/news/how-to-manage-virtual-memory-pagefile-windows-10,36929.html).

## Reloading Saves

Reloading saves frequently in Skyrim can negatively impact the game's stability. Skyrim's engine, known for its quirks, sometimes retains data from previous sessions even after a save is loaded. This can lead to increased memory usage, potential save file corruption, and more frequent crashes. By avoiding frequent reloads and instead playing continuously from a single save point, you help ensure smoother gameplay and reduce the risk of encountering these technical issues. [Learn more](https://www.youtube.com/watch?v=PJPzMAXSprU).

## Also Try

- **Lower Resolution:** Try running on a lower resolution. You can set the resolution in `F:\LoreRim\mods\LoreRim - MCM and INI Settings\SKSE\Plugins\SSEDisplayTweaks.ini`.

- **VRAMR:** Try running [VRAMR](https://www.nexusmods.com/skyrimspecialedition/mods/90557).

- **BethINI:** Use [BethINI](https://www.nexusmods.com/site/mods/631) and choose a lower INI setting. Lorerim is based around the High setting with custom tweaks.

- **Disable TexGen and DynDoLod Outputs:** You may need to start a new game if you disable these.

- **Disable ENB Completely:** Disabling ENB can significantly improve performance.
