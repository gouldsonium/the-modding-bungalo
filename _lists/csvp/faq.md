---
layout: default
title: FAQs
parent: CSVP
nav_order: 2
---
# Frequently Asked Questions
Please checkout these FAQs before posting your question to the discord

### What is CSVP?
CSVP is a Vanilla Focused modlist built upon the visuals in "Next Generation Visual Overhaul". It is intended as a packaged experience you can play immediately after download, but is sparing enough in sweeping overhauls to allow customization.

Skyrim Anniversary Edition with the full $20 upgrade is required. CSVP runs on version 1.6.1170.

The list is built on AE Edition but I cut out or modified a lot of the content that AE includes, either for Lore reasons or personal taste. Disabled AE Content Includes:
- Sunder & Wraithguard
- Umbra
- Staff of Sheogorath
- Divine Crusader
- Arms of Chaos
- Bow of Shadows
- Plague of the Dead
- Dawnfang & Duskfang
- Saturalia
- Shadowfoot Sanctum
- Bloodchill Manor
- Hendraheim
- Civil War Champions (You just get the Armor in the Civil War Questline now),

I am a proud Vanilla Apologist, and the only goal for this list was a fresh coat of paint for the crowning game of my childhood. The list has Survival turned ON by Default and Fast Travel disabled (but still possible through an item), it is set on a scaled Master Difficulty with my custom settings for Experience gain and Level Curve. These settings are configurable with know-how but options are not neatly presented to you as this list focuses on my singular vision. The list works with the Vanilla Cart Opening but it is optional, should you choose to skip the intro you will start at the end of the Helgen cave, and a chest with starter items will be outside under a tree to your right. I have added no custom followers, no new lands, and no sweeping changes to systems like Combat and World Scaling (AKA No Requiem, no MCO, etc). I opted to enhance what was present already instead!

### Are there multiple profiles?

CSVP comes in two versions: Main and Performance

To download CSVP, select a version from the 'Main Files' section of my Nexus Downloads tab. That is the Wabbajack File and the only thing you personally need to download from the Nexus Page. From there you want to open Wabbajack and do the following:

Go to 'Browse Lists', select 'Install from Disk' in the top right,
Select the CSVP Wabbajack file you downloaded from Nexus,
Set the installation folder to be somewhere like C:\CSVP. Do not install it to your desktop, downloads folder, or program files folders,
The download location does not have to be an SSD but it makes the install faster. The Download and Installation locations also do not have to be the same if you have storage concerns,
See the ReadMe for Pre Installation Steps and further instruction,

The two versions are completely identical gameplay and backend systems-wise. The difference is strictly visual and performance focused; CSVP Main can use up to 10.5GB of VRAM in the most taxing areas, Performance uses downscaling and a different combo of flora mods to limit that to 7.5. As of Update 2.1 Performance is also on ENB, and FrameGen is an included Optional for BOTH versions of CSVP and still OFF by default so users can experiment for themselves post install! 

![Image]({{ site.baseurl }}/assets/csvp/community-shaders.png)

## Can I use a controller?

Switching to the controller config is 2 easy steps (See the video). Bind Dual Wield Block to L1 in Valhalla's MCM and activate the 'Controller Config (ON)' profile in the MCM Recorder Menu, that's it! To switch back from controller you will bind Dual Wield Block back to V, and activate the 'Controller Config (OFF)' profile.

See the bind maps below. Hotkeys 1-6 need to be set by the Keyboard as they are mapped but not able to be designated by the Gamepad itself.

Reminder that with STB Hotkey Quick Cast you can swap between Powers and Shouts on the fly without going into menus by binding them to a hotkey!
![Image]({{ site.baseurl }}/assets/csvp/controller.png)

## What are the hotkeys in this list?

- **ENB:** SHIFT+ENTER
- **Community Shaders:** END
- **KreatE:** HOME
- **Open Animation Replacer:** SHIFT+O
- **Immersive Equipment Displays:** BACKSPACE
- **Improved Camera SE:** SHIFT+HOME
- **SmoothCam Toggle:** UP ARROW
- **Switch Shoulders (*SmoothCam*):** M4 (Mouse Side Button)
- **Third Person Zoom In/Out:** M5 (Mouse Side Button)
- **Simplest Horses:** H
- **iHUD/moreHUD:** X
- **Toggle HUD:** N
- **Dual Wield Blocking:** V
- **AutoHorse:** B
- **Teleport Followers to You:** G
- **Hotkey Reminder:** F11 

## How do I add Grass LODs?

If you want to spruce up visuals without much effort, you could try adding Grass LODs. First, remove the TexGen and DynDOLOD Outputs that are currently in your Outputs Separator. Rerun TexGen, following the images below to select the Grass LOD option, and install it's zipped Output. Repeat this for DynDOLOD (Grass LOD will not be greyed [Image 2] if you do the TexGen step correctly). If you decide in the future that you want dont Grass LODs after all, simply redownload the Performance Outputs from the Nexus Page and replace the ones you have created!

I will not be including guides on creating your own Grass Cache if you would like to swap to different Mods. There are plenty of helpful guides that I used to make this list, and they will serve you just as well.

![Image]({{ site.baseurl }}/assets/csvp/texgen.png)

![Image]({{ site.baseurl }}/assets/csvp/dyndolod.png)

## How do I swap to ENB?

On the other hand if you have PC Power to spare and would like an extra Graphical boost, you could swap to ENB. Turn your Community Shaders separator into an ENB section by emulating the image below* (for how to set up an ENB, look for the ENB part of this FAQ)[Remember to read Flagged Notes on Mods for specific intructions]. Go into your Outputs Separator, find 'CSVP - MCM & INI Settings' and delete the folder named 'ShaderCache' inside. Be sure to also delete the contents of the 'KiLoader Output' in the same Separator. Upon closing the game after first launch you will have newly generated ShaderCache folders and KiLoader folders in your Overwrite, place them back in their respective mods accordingly.

*You do not need multiple KreatE installations when emulating the image
**As of Update 2.1, Performance is on ENB already. Will leave this guide up anyway

![Image]({{ site.baseurl }}/assets/csvp/switch-to-enb.png)

## What if I want to make changes to the list?

## MAKING CHANGES TO THE LIST

The image below is the correct order for rerunning your Gamut (if you are Precaching Grass, do it after ParallaxGen), for reference:

- LODGen = Terrain LODs
- TexGen = Billboards
- DynDOLOD = LODs
- ParllaxGen & VRAMr = Textures & Meshes

__RUN SYNTHESIS BEFORE__. These are your final steps, so if you are adding 10 mods you will do all of this AFTER ALL TEN ARE INSTALLED not after each mod. Furthermore, adding a mod does not always mean you have to rerun the Outputs. Read the Mod Page thoroughly, and dont be afraid to ask!

**Performance Users NOTE:** VRAMr (the program) is not included in CSVP, I created the Output and then removed it. If you are redoing your Outputs visit the VRAMr page to download the program, and while you're there follow along with the video the dev himself made!

Do not make official Reports for bugs if you have made ANY changes to the list, you're welcome to ask for help in the chats though.

![Image]({{ site.baseurl }}/assets/csvp/loadorder.png)

## ENB - Adding or Changing

### Adding
With Root Builder, an ENB can be setup like a Mod in your Organizer so you can freely swap between Presets!

**Step 1:** Reading - When you choose the ENB you'd like (in this case Cabbage) you have to go over it's requirements and ensure you have everything it needs to work properly. You can lookup mods in your Organizer with the Search Bar in the bottom right of the respective Pane. In Cabbage's case, we only need the Shader Core and the ENB preset itself!

{: .important}
Remember that modifying the list does not fall within the guidelines of receiving proper help in the event of issues

**Step 2:** Make it a Mod - Create an Empty Mod for each of the ENB Related things you are adding (again, in Cabbage's case we are making an empty mod for the Shader Core and another for Cabbage itself). Inside the empty mod create a folder named 'Root', place the necessary files into your Root Folder (see Step 1 on Reading to know which files are needed for your chosen ENB) and then Activate the mod.

That's it! You can now have multiple ENBs and swap between them on the fly, but beware that some ENBs (like Dawnfire in CSVP) have .esp plugins that are placed in the list, so removing them mid-playthrough is NOT recommended! You are encouraged to find a look that suits you best before jumping in.

### Changing

If you're a Main user wanting to change ENB, or a Performance user swapping over, this will help!

Navigate to the ENB Separator, uncheck Dawnfire and the Dawnfire KreatE Preset. Check the Standard NAT3 KreatE Preset, as well as Silent Horizons Shader Core and Cabbage

In your Outputs Separator there is a mod named 'ENB Cache', go in and delete the folder named Root. When you close the game a new Root folder will be in your Overwrite that you can place in the ENB Cache mod. Every time you swap ENBs you must delete that folder

Once again, DAWNFIRE ENB HAS AN ESP PLUGIN so decide what ENB you want before starting your playthrough, as swapping plugins is bad for your save.

## How do I switch to Community Shaders on Main

Replace your ENB Section with a Community Shaders section and copy the image below. You will also need to reinstall the KreatE Preset to select the CS version of NAT3 Weathers, delete the contents inside 'KiLoader Output', and delete any/all enbcache, enbseries, and enbbackup folders (located CSVP\mods\CSVP - MCM & INI Settings\Root).

**As of Update 2.1 the list uses ENB Terrain Helper which is, at this time, not officially supported by Community Shaders. It is not recommended to use Community Shaders with CSVP until there is Compatibility. 

![Image]({{ site.baseurl }}/assets/csvp/enb-to-cs.png)