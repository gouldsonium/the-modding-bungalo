---
layout: default
title: Modification Manual
parent: Guides
grand_parent: CSVP
nav_order: 2
---
# Modification Manual

{: .warning}
>**WARNING**
>
> Do not make official Reports for bugs if you have made ANY changes to the list, you're welcome to ask for help in the chats though.

## MAKING CHANGES TO THE LIST
The image below is the correct order for rerunning your Gamut (if you are Precaching Grass, do it after xLODGen), for reference:

- xLODGen = Terrain LODs
- TexGen = Billboards
- DynDOLOD = LODs
- ParallaxGen & VRAMr = Textures & Meshes

RUN SYNTHESIS FIRST. These are your final steps, so if you are adding 10 mods you will do all of this AFTER ALL TEN ARE INSTALLED not after each mod. Furthermore, adding a mod does not always mean you have to rerun the Outputs. Read the Mod Page thoroughly, and dont be afraid to ask!

*If you are rerunning your Outputs, disable or delete all current Outputs as they will only hinder you*

**Performance Users NOTE:** VRAMr (the program) is not included in CSVP, I created the Output and then removed it. If you are redoing your Outputs visit the VRAMr page to download the program, and while you're there follow along with the video the dev himself made!

## Synthesis

This should always be your first stop after adding/patching all of your mods. The image below is what CSVP uses. If you get a "too many masters" error, you can split the patches up into multiple groups. Each Skyrim plugin can only have 254 plugins as its master. Synthesis has a lot of good patches and most have descriptions but these are typically on an as-needed basis when it comes to adding them.

When updating Synthesis, ensure in the Settings that it points to the Data folder for the modlist (e.g CSVP\Stock Game\Data)
![Image]({{ site.baseurl }}/assets/csvp/synorder.png)

## VRAMr
VRAMr is a tool meant to optimise all of your texture mods including PBR, Parallax and Complex Material. No scripts, no ESP and no need to start a new game! If making your own VRAMr Output, ensure you delete the current Output or it will not work.

1. To begin, install VRAMr as a regular mod and activate it (Load Order is irrelevant)
2. From the dropdown menu in the top right of MO2, select <Edit...> to bring up the Modify Executables Menu
3. Select the + symbol in the top left, navigate to 'Add from File'
4. Add the VRAMr.bat file as an Executable, this should be located at CSVP\mods\VRAMr\VRAMr
5. Ensure you check 'Force Load Libraries', hit Apply and OK, then run VRAMr through MO2
6. Follow the prompts and steps the Program walks you through, select the level of Optimization you desire
7. Select where the Output will Generate for now (I recommend just selecting the drive with the most space [e.g D:\VRAMr])
8. Select the Profile you wish VRAMr to target (e.g CSVP\Profiles\CSVP - Main) and it will begin
9. When it has finished, you can create an Empty Mod in MO2 and place the Output files inside

The VRAMr Nexus Page includes many wonderful video guides including one from the Dev himself! Please refer to these if stuck

## ParallaxGen
This program is the easiest and fastest of the Modification Steps. As always, ensure you delete the current Output or it will not work. If you converted CSVP to use PBR (Community Shaders users) you probably want to enable that option here, and if you swapped from ENB to CS you will want to uncheck 'Fix Mesh Lighting' in the top right (not pictured).
![Image]({{ site.baseurl }}/assets/csvp/pgpatcher.png)

## xLODGen
Before beginning, enable 'xLODGen Resource - SSE Tamriel' in the Mod Tools & Resources Separator. Place the plugin in the Mod Resources Group under 'Bittercup - Tweaks and Enhancements.esp'. You may now launch xLODGen through MO2.

NOTE - There are 4 LODs (levels of detail) to change meaning you need to enter the settings for each one of them (hence the 4 images). These settings should already be set in CSVP and ready to go!

When you're finished and have added your new Output, remember to disable 'xLODGen Resource - SSE Tamriel'

See this [video from Biggie_Boss](/modding_guides/lodgen/xlodgen/) if anything isn't clear enough, or you prefer visual learning

## Grass Cache
This will only ever need to be done if you have changed the Grass Mod or added a Worldspace, and you want Grass LODs.

You are encouraged to follow [Biggie's Guide](modding_guides/lodgen/grasscache/), it's how I learned and he will explain far better than I can write out!

**NOTE - To ensure a smooth process, make a new Profile and name it 'Grass Cache' when doing the steps in the video. Prior to running your Grass Cache you will want to disable SkyrimSouls RE in the Gameplay & Systems Changes Separator, as well as EVERYTHING in the ENB (or CS if you use it) Separator, and EVERYTHING IN ALL 3 UI SEPARATORS. When finished Precaching you can simply swap back to your Default Profile and everything you had disabled should be back to normal!**

### PERFORMANCE - ADDING GRASS LODS
If you are a Performance User and think you can squeeze out extra fidelity, you could try adding Grass LODs! I've already Precached the Grass for you so the process is simpler than doing it from scratch with a different Grass Mod. First, remove the TexGen and DynDOLOD Outputs that are currently in your Outputs Separator. Rerun TexGen, following the images below to select the Grass LOD option, and install it's zipped Output. Repeat this for DynDOLOD (Grass LOD will not be greyed [Image 2] if you do the TexGen step correctly). If you decide in the future that you want dont Grass LODs after all, simply redownload the Performance Outputs from the Nexus Page and replace the ones you have created!

![Image]({{ site.baseurl }}/assets/csvp/texgen.png)

![Image]({{ site.baseurl }}/assets/csvp/dyndolod.png)

## TexGen
This program is one of the easier ones, see the image for the settings I use - Main Users will/should have the 'Units Per Pixel' value set to 8.0 (1440p)

![Image]({{ site.baseurl }}/assets/csvp/texgen_output.png)

## DynDOLOD

You should not need to modify any settings for CSVP, but they are provided in the image just in case (please note the Mountain and Azura statue Rule, right click and select Insert to make these if needed). There are also settings in the DynDOLOD_SSE.ini that have been customized, you should not need to do this yourself either but if that isn't the case you will navigate to **CSVP\tools\DynDOLOD\Edit Scripts\DynDOLOD** and and change the following:

```
; Billboard template to use for grass LOD billboards created from "normal" grass without normal map textures
; 1 -> Billboard1, 2 -> Billboard2, 3 -> Billboard3 etc.
GrassBillboard=1

; Billboard template to use for grass LOD billboards created from "complex" grass with normal map textures
; 1 -> Billboard1, 2 -> Billboard2, 3 -> Billboard3 etc.
ComplexGrassBillboard=5

; grass LOD brightness multipliers - applied to grass LOD billboards created from "normal" grass without normal map textures
GrassBrightnessTopR=0.610
GrassBrightnessTopG=0.600
GrassBrightnessTopB=0.580
; make bottom darker to fake shadowing
GrassBrightnessBottomR=0.610
GrassBrightnessBottomG=0.500
GrassBrightnessBottomB=0.280

; complex grass LOD brightness multipliers - applied to grass LOD billboards created from "complex" grass with normal map textures
ComplexGrassBrightnessTopR=0.610
ComplexGrassBrightnessTopG=0.600
ComplexGrassBrightnessTopB=0.580
; make bottom darker to fake shadowing
ComplexGrassBrightnessBottomR=0.510
ComplexGrassBrightnessBottomG=0.500
ComplexGrassBrightnessBottomB=0.480

; glowmap and backlighting mask textures replacements if corresponding texture slot is set by used grass billboard NIF
; 0 = keep texture defined in billboard NIF
; 100 = textures\white.dds
; other values generate and use a 4x4 pixel grayscale texture with RGB = 255 * value / 100
GrassGlowMap=0
GrassBacklightMask=0
ComplexGrassGlowMap=0
ComplexGrassBacklightMask=50
```

[Video Guide from Biggie_Boss](/modding_guides/lodgen/dyndolod/)

## COMMUNITY SHADERS
Replace your ENB Section with a Community Shaders section and copy the image below NOTE - this image is old and will be missing newly released features for CS, always read the Mod Page and get everything you need. You will also need to reinstall the KreatE Preset to select the CS version of NAT3 Weathers, delete the contents inside 'KiLoader Output', and delete any/all enbcache, enbseries, and enbbackup folders (located CSVP\mods\CSVP - MCM & INI Settings\Root).

![Image]({{ site.baseurl }}/assets/csvp/enb-to-cs.png)

## ENB - ADDING OR CHANGING
### Adding
**With Root Builder, an ENB can be setup like a Mod in your Organizer so you can freely swap between Presets!**

*Step 1:* Reading - When you choose the ENB you'd like (in this case Cabbage) you have to go over it's requirements and ensure you have everything it needs to work properly. You can lookup mods in your Organizer with the Search Bar in the bottom right of the respective Pane. In Cabbage's case, we only need the Shader Core and the ENB preset itself!

*Remember that modifying the list does not fall within the guidelines of receiving proper help in the event of issues*

*Step 2:* Make it a Mod - Create an Empty Mod for each of the ENB Related things you are adding (again, in Cabbage's case we are making an empty mod for the Shader Core and another for Cabbage itself). Inside the empty mod create a folder named 'Root', place the necessary files into your Root Folder (see Step 1 on Reading to know which files are needed for your chosen ENB) and then Activate the mod.

That's it! You can now have multiple ENBs and swap between them on the fly, but beware that some ENBs (like Dawnfire in CSVP) have .esp plugins that are placed in the list, so removing them mid-playthrough is NOT recommended! You are encouraged to find a look that suits you best before jumping in.

### Changing
**If you're looking to change ENB, this will help!**

Navigate to the ENB Separator, uncheck Dawnfire and the Dawnfire KreatE Preset. Check the Standard NAT3 KreatE Preset, as well as Silent Horizons Shader Core and Cabbage

In your Outputs Separator there is a mod named 'ENB Cache', go in and delete the folder named Root. When you close the game a new Root folder will be in your Overwrite that you can place in the ENB Cache mod. Every time you swap ENBs you must delete that folder

Once again, DAWNFIRE ENB HAS AN ESP PLUGIN so decide what ENB you want before starting your playthrough, as swapping plugins is bad for your save.

