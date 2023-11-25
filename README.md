# [HLMV++](https://developer.valvesoftware.com/wiki/HLMV%2B%2B)
**HLMV++** *(Half-Life Model Viewer++)* is a new build of HLMV created by ficool2. The goal is the same as **[Hammer++](https://ficool2.github.io/HammerPlusPlus-Website/)**, to fix long-standing bugs in HLMV and add new features and functionality to make the program better to use, whether you're doing model renders for artwork or for wiki articles.

Want more information on why you should try HLMV++? Check out **[this GameBanana blog post by user Tunnel](https://gamebanana.com/blogs/20066)**! Major thanks to Tunnel for writing that lovely blog post ❤️

# Linkage
- Interested in making those fancy 3D rotateable model renders for the Official Team Fortress 2 Wiki with HLMV++? **[Check out 3D Models Automaton by @jbzdarkid](https://github.com/jbzdarkid/3D-Models-automaton)!**
- **[Click here](https://discord.gg/pB86MBCzkd)** to join the HLMV++ Discord server where you can report bugs and suggest new features.
- Follow us on Twitter at **[@HLMVPlusPlus](https://twitter.com/HLMVPlusPlus)** for new release announcements and sneak peeks of new features.
- We also have an article on the Valve Developer Community Wiki: **[HLMV++](https://developer.valvesoftware.com/wiki/HLMV%2B%2B)**.
- There is also now a proper **[Wiki](https://github.com/ImguRandom/HLMVPlusPlus/wiki)** for this repo.
  - Wiki is currently under construction.

# Source Code?
**HLMV++, like ficool2's other project, **[Hammer++](https://ficool2.github.io/HammerPlusPlus-Website/)**, is closed source. Due to ficool2 being a licensed Source Engine developer, the source code for HLMV++ cannot legally be released.**

# Supported Games
- Team Fortress 2
  - Can also work with the various Team Fortress 2 Source mods like TF2Classic, Pre-Fortress 2, Open Fortress and Team Deathmatch Classic.
  - **[Follow this guide on setting up HLMV for Pre-Fortress 2](https://steamcommunity.com/sharedfiles/filedetails/?id=2784234957)**, but instead of creating a shortcut for hlmv.exe, create it for hlmvplusplus.exe. Then add the -game parameter to the Target field of the shortcut as normal and point it to whichever mod's directory. If you have issues with this, please join the HLMV++ Discord and we can assist you further. 
- Left 4 Dead 2
- Garry's Mod

## Coming soon
- Portal 2
- Source SDK MP2013 (which means the shortcut trick won't be necessary to get this working for TF2 mods and other Source game mods)

# Installation
Download the EXE and the DLL files from this repo and extract them into your `steamapps/common/<game>/bin` folder *(where `hlmv.exe` is stored)*. Then just launch `hlmvplusplus.exe` instead of `hlmv.exe` and you're done!

For Garry's Mod, if you are playing on the 32 bit build, just extract `hlmvplusplus.dll` and `hlmvplusplus.exe` and leave the rest of the DLLs. If playing on the 64 bit build, extract the entire package.

# Old Builds
Old historical builds are also hosted here for posterity. Do note that older builds may contain some bugs and other issues that have been fixed in more recent versions, and will obviously lack any new features present in the most recent builds. If you are using an older build and encounter a bug, it is recommended to upgrade to the most recent build. If reporting a bug on the HLMV++ Discord, support will not be granted for bugs in old builds.

# Fixes & New Features
For a full list of all new features and general fixes in HLMV++, please check out the **[Version History](https://github.com/ImguRandom/HLMVPlusPlus/wiki/Version-History)** article on this repository's Wiki.

# Known Issues
We can't really fix these at the moment.
- The **Make Screenshot** function may not work correctly when HLMV++ is stretched across multiple monitors. Doing so may result in a very wide screenshot with two copies of the same model in it. This is, to my knowledge, not fixable.
- Making transparent screenshots/videos of anything that uses `$additive` materials, such as certain particle effects in TF2, does not work correctly as the generated alpha channel algorithm doesn't play nice with additive materials. Any details that use additive materials will not be part of the generated alpha channel.

# Credits
- **ImguRandom** - Commissioned the creation of this project.
- **[ficool2](https://github.com/ficool2)** - Programming. The entire reason this even exists.
- **[Gabrielwoj](https://github.com/gabrielwoj)** - Bug testing, providing feedback and insight on changes/new features. Also made the Discord server image.
- **[Andrew360](https://wiki.teamfortress.com/wiki/User:Andrew360)** - Bug testing, providing feedback and insight on changes/new features.
- **[ArielChandia2](https://twitter.com/ArielChandia2)** - Bug testing.
- **[A Paint Bucket Named Huey](https://github.com/HueyCan)** - Bug testing.
- **Everyone who has reported a bug or submitted a feature request on the HLMV++ Discord** - 
Too many of you to list, but your contributions are all greatly appreciated ❤️
