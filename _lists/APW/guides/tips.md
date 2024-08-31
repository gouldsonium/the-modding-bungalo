---
layout: default
title: Tips
parent: Guides
grand_parent: A Painted World
nav_order: 2
---
# Tips
Tips from **Sasquatch**, the modlist author
## Safe to modify - not rule 11

You can disable the oil painting and bumpmapping shader in reshade by unchecking them in the reshade ui after pressing the home key. You can turn off Reshade entirely by disabling the Reshade mod in mo2 or pressing the end key. These effects do alter the ui of the game so text will be easier to read with them off. May very slightly increase performance.

Anything in the optional mods separator or ultrawide separator.

## Optional performance/stutter prevention steps

Open the mod Oblivion BSA Decompressor, run the Oblivion BSA Decompressor.exe, point it to the Stock Game folder, and click the big red button that says Decompress.

Open each ini file in mods\Culling Settings\ini\CitySettings and reduce each setting until you no longer have issues.

## Known Issues: 

1. On the main menu the background of the confirmation box when starting a new game is transparent. Darnified UI issue.

2. The Save Game screenshot has a black bar/graphical artifacting. This is an issue when running the game at higher resolutions. Remember, Oblivion was originally intended to be played on 4:3 aspect ratios.

3. For some of you Reshade doesn't seem to install properly but it is safe to install it yourself. You can test whether it is working by pressing the home key. If no menu appears, it is not working. You can download it [here](https://reshade.me/downloads/ReShade_Setup_6.2.0.exe). When it asks, point it to the Oblivion.exe in the Stock Game folder wherever you installed the mod list. Select Vulkan when given the prompt, and uncheck all effects. 

4. The game can stutter or fps can drop quite heavily in certain areas. Oblivion is an old game on a 32bit engine, I have done and am still doing what I can to alleviate this as much as possible. Elsewyr cities in particular tank fps.