#PocketMine Plugin for protecting areas
CustomAreas is a plugin that provide players a way to protect their buildings using simple commands.

Current features:
-Create private areas where other players cannot build
-Provide protection for blocks, chests, doors and trapdoors inside the area
-Whitelist for areas: an area owner can choose who can build in his zone
-Support for multi-world
-Bypass feature for OPs: they can edit other players areas (or use permission node customareas.bypass)
-Easy to use
-Configurable

Command | 
------------ | -------------
/ca | null
Content in the first column | Content in the second colum


Commands:
Main Command: /customareas
Aliases: /ca, /area, /areas
The alias /area may conflict with iProtector
/ca pos1 : set the first corner of the area
/ca pos2 : set the second corner of the area
/ca create : create an area with the current selection
/ca delete : delete the area where you are standing in (OPs can delete other players areas)
/ca whitelist add <player> : add a player to the whitelist of the area where you are standing in (OPs can edit other players areas whitelist)
/ca whitelist remove <player> : remove a player to the whitelist of the area where you are standing in (OPs can edit other players areas whitelist)
/ca whitelist list : see the list of the whitelisted players of the area where you are standing in (OPs can see other players areas whitelist)
