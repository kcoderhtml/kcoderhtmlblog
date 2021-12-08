+++
title = "Clientside Fabric ModPack"
description = "A Clientside Modpack -- The modpack for KlukasCraft"
date = 2021-11-20T08:55:44Z
author = "Kieran Klukas"
draft=false
+++
# KlukasCraft ModPack -- A Post.
---
Welcome to my post about the KlukasCraft ModPack. It has these mods:
* Simple Hud Utilities v2.3.0
* Camera Overhaul v1.3.0
* Falling Leaves v1.8.0
* Mod Menu v3.0.0
* Better F3 v1.2.0
* Cloth Config API v6.0.42
* Simple Voice Chat v2.1.16
* Not Enough Crashes v4.1.3
* Not Enough Animations v1.4.0
* Fabric API v0.44.0
* Accurate Block Placement v1.0.11
* Cloth API v2.0.54    

## Simple Hud Utilities
A Mod that enhances the Game's HUD with some simple utilities like the following:
- HUD Features:
  - Simplified coordinates that are available at all times on the screen (Example: 39, 64, 200 as X, Y, Z)
  - Cardinal directions and which Coordinates are increasing/decreasing (Example: (East X+) when looking East, where the X coordinate is increasing)
  - Current armour and hand items and their durabilities, available at all times on the screen
   - Different colors based on how low the durability is
   - Current Game time in AM/PM format
   - Current sprinting status
   - Current framerate
   - Current Biome the player is on
   - Toggle key (editable in Controls screen, default is 'k')
   - Settings page and config file with Mod Menu
## Camera Overhaul
It's a clientside mod that attempts to improve overall satisfaction of the game through the introduction of various camera rotations, to emphasize on the player's movement and improve visual feedback. Strafing and turning around will tilt the camera sideways. Jumping, falling, and moving forward/backwards will affect the camera's pitch.
## Falling Leaves
This Fabric mod for Minecraft 1.18 adds a neat little particle effect to leaf blocks. Users can configure which types of leaf blocks will drop leaves and the frequency that these leaves are dropped at.
## Mod Menu
Adds a screen for viewing a list of installed mods.
  - The menu is searchable and sortable, libraries can be hidden.
  - Client-side and API mods are marked with a special badge in the list.
  - When clicking a mod in the list, its homepage, issues link and description are displayed.
  - The mod details page also lets the user configure the mod, if available (can be disabled for modpacks via config). 
## Better F3
BetterF3 is a mod that replaces Minecraft's original debug HUD with a highly customizable, more human-readable HUD. You can customize colors, position, add spacings, and more.

  - Change the colors of each module
  - Change the position of each module
  - Add and delete modules, as well as add spacings between them
  - Disable individual lines of a module, or disable the whole module
  - Add a shadow to the text rendered (Activated by default)
  - Change the color of the background behind all lines
  - Animations for opening/closing (with configurable speeds)
## Cloth Config API
Cloth Config API is a config screen api.
## Simple Voice Chat
This mod adds a proximity voice chat to your Minecraft server. You can choose between push to talk (PTT) or voice activation. The default PTT key is CAPS LOCK, but it can be changed in the controls. You can access the voice chat settings by pressing the V key.

  - Proximity voice chat
  - Password protected group chats
  - Opus codec
  - RNNoise recurrent neural network noise suppression
  - Cross compatibility between Fabric, Forge, Bukkit, Spigot and Paper
  - Compatibility with Sound Physics Remastered
  - Compatibility with Sound Physics Fabric (Not recommended)
  - Compatibility with ModMenu (Use ClothConfig for a better configuration UI)
  - Push to talk
  - Voice activation
  - Configurable PTT key
  - Test microphone playback
  - Indicator on the screen when you are talking
  - Indicator next to players names when they are talking
  - Configurable voice distance
  - Whispering
  - Mute other players
  - Adjust the volume of other players
  - Microphone amplification
  - 3D sound
  - AES encryption
  - Configurable network port
  - Audio recording
## Not Enough Crashes
Not Enough crashes is a Minecraft mod that improves crashes in Minecraft. If the game is closing with no crash screen or log, enable forceCrashScreen in the configuration! Fabric is supported for all versions. Go here for Forge downloads.
NEC can be installed on the client and server independently.

  - When crashing, you can go back to the title screen and keep playing, without needing to restart.
  - A convenient way to submit syntax-highlighted crash reports via a special crash screen.
  - Display a list of mods that were involved in the crash, and can be clicked to go to their issue tracker.
  - More useful stack traces that are deobfuscated and include additional information such as NBT for mod developers.
  - Force crash logs to always appear (forceCrashScreen). See tutorial for how to change configuration.
## Not Enough Animations
This mod brings a lot of missing third-person animations from the first-person or modifies them to be better representative to how they should look like or look like in the first-person. This mod was created as an expansion for the First-Person Mod, but works completely on its own and is fully vanilla/3rd party server compatible(since it's all just visual).

  - Eating/Drinking
  - Maps(Yes you can see the map content if your client has been sent the map by holding it once/seeing it in an item frame)
  - Shield placement(you block where you look, not where the body is rotated to. So this will rotate the body with the head while blocking)
  - Don't show items during two-handed animations(Hide the offhand item while using a bow/crossbow)
  - Boat rowing(No longer sitting there and staring at the self-moving Paddles)
  - Horses(at least act like you're holding the reins)
  - Looking at a compass/clock(this one is actually more eye candy for the First-person Mod to make the compass better usable, but won't hurt outside of that, can be modified in the config file to extend to more items)
  - Ladder/climbing animation
  - Crawling animation, replacing the swimming one while out of water
  - Smooth arm movement and transitions
  - Scabbard Sword while not in use
## Fabric API
Fabric API is the core library for the most common hooks and intercompatibility measures utilized by mods using the Fabric toolchain
## Accurate Block Placement
Inspired by the excellent 1.12.2 mod BetterPlacement. This is an 100% client side mod. You can put it on a server, but it won't do anything. Although many experienced minecraft players know exactly how to time their clicks in order to rapidly place blocks with no mistakes, why should it be that difficult? In this mod, if you hold your 'use key' (usually RMB) and look at a new block it will automatically place it no matter how fast you move. No more need to time when you click or look in order to accurately place blocks quickly! You can set a keybind in the controls menu for switching to and from standard vanilla placing behavior.
## Cloth API
Cloth API is a generalized api.  

---

Thanks for Reading! I hope these mods may help your minecraft worlds and servers come alive.
