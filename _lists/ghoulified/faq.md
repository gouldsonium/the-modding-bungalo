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

I am a proud Vanilla Apologist, and the only goal for this list was a fresh coat of paint for the crowning game of my childhood. The list is built on AE Edition but I cut out or modified a lot of the content that AE includes, either for Lore reasons or personal taste. I have added no custom followers, no new lands, and no sweeping changes to systems like Combat and World Scaling (AKA No Requiem, no MCO, etc). I opted to enhance what was present already instead!

### Does the require CC?

Skyrim Anniversary Edition with the full $20 upgrade is required. CSVP runs on version 1.6.1170.

### Are there multiple profiles?

CSVP comes in two versions: Main and Performance

The two versions are completely identical gameplay and backend systems-wise. The difference is strictly visual and performance focused; CSVP Main can use up to 10.5GB of VRAM in the most taxing areas, Performance limits that to 7.5. CSVP - Performance comes with the latest updates for Community Shaders and as such includes Upscaling and Frame Gen, these are OFF by default so users have even more headroom to work with post install! See the image below to know where to find the settings, access the Community Shaders Menu with the END key on your Keyboard.

![Image]({{ site.baseurl }}/assets/csvp/community-shaders.png)

### I want more fidelity on performance profile

I have done the due diligence of running Grass Cache for you already, all you have to do is rerun your TexGen and DynDOLOD with the options checked (see the images below)

![Image]({{ site.baseurl }}/assets/csvp/dyndolod.png)

![Image]({{ site.baseurl }}/assets/csvp/textgen.png)

### I want to switch to Community Shaders without switching to Performance

Replace your ENB Section with a Community Shaders section and copy the image below. You will also need to replace your Cubemaps and delete your enbcache, enbseries, and enbbackup folders (located `CSVP\mods\SKSE & MCM Output\Root`) 

![Image]({{ site.baseurl }}/assets/csvp/mo2-cs.png)

![Image]({{ site.baseurl }}/assets/csvp/mo2-cs-overrides.png)

### What are the hotkeys in this list?

- **ENB:** SHIFT+ENTER
- **Community Shaders:** END
- **KreatE:** HOME
- **Open Animation Replacer:** SHIFT+O
- **Immersive Equipment Displays:** BACKSPACE
- **Improved Camera SE:** SHIFT+HOME
- **SmoothCam Toggle:** UP ARROW
