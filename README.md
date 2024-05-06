# Quake 2 - Celeste Mod (more like I accidentally made an Ultrakill mod)

## Description:

Celeste, a 2D platformer game, has a lot of unique movement features and obstacles that makes it more distinct from other platformers. However, Celeste is obviously not made to work in an FPS environment, but this mod tries to create an experience as if it were meant for that. To comply with the deliverables, the features added to this mod aren't specific to Celeste, involving ideas from myself or inspiration from other movement shooters. 

## Download Instructions:

Download the 'mods' folder from Releases
Unzip mods and then place the folder in your Quake 2 folder (Usually located here: C:\Program Files (x86)\Steam\steamapps\common\Quake 2)
If necessary, go to the Properties of the 'quake2 - MOD' and change the directory to be your Quake2 directory inside the 'Target:' bar so that you can actually play the mod (DONT CHANGE +set game mods)

**NOTE: This mod does NOT work with the remastered version. If opening the mod with the shortcut provided with the folder somehow opened the remastered version, you can follow an alternate method if you own the game on Steam. Unfortunately, this is the only other way I know of.**
### Alternate Play Instructions:

If you don't want to open the game this way or the shortcut opened the remastered version, you can launch the game through Steam instead:
1. Find Quake 2 in your Steam library and right click on it then go to properties as shown in the image below:

![image](https://github.com/Alzabun/Quake2Celeste/assets/29514225/9fe6c7dd-b0be-47c8-b6a8-59666e324168)

2. Navigate to the 'General' tab on the sidebar, then look for the Launch Options.
3. The default setting is to 'Ask when starting game'. You must click on that and switch it to 'Play Quake II original'.

4. For the actual launch options, they act as a shortcut to open the game, so just like manually making a shortcut to the mod, add the parameters '+set game mods' to the launch options

![image](https://github.com/Alzabun/Quake2Celeste/assets/29514225/c7665126-3569-480f-ad96-452163e81e58)

## How To Play

To see if the mod is actually working, you can enter a single-player game or a death match game. You'll know for certain that it's working because there are UI elements relating to the mod's features that are hard to miss. If they are somehow not there and you know the mod is working, press F1.

A guide on exactly everything the mod changes can be found ingame. To find this, open the console (CTRL + ALT + `) and type in "modhelp". You can use this as many times as you want without having to come back to here to remember how to play. However, a list of every change will be here as well:

### Movement Abilities

Dash - Press E in the air [CONSUMES 5 STAMINA]: Fly towards the direction your facing (Can only be used in the air) (Celeste's main form of movement)
Slide - Hold C then press CTRL [CONSUMES 0 STAMINA]: Slide in the direction your facing (Can only be while crouching) 
Float - Press F in the air [CONSUMES 1 STAMINA EVERY SECOND]: Hover in the air for a short period of time (Can only be used in the air)
Climb - Press V next to a wall [CONSUMES 1 STAMINA EACH CLIMB]: Climb up a wall (Celeste's other main form of movement)
Smash - Press Z in the air [CONSUMES ALL STAMINA]: Slam into the ground causing a massive explosion. The higher in the air you are the more powerful the explosion. Be careful though since this move will hurt a lot if abused too much.

### Weapon Changes

Strawberry Launcher (Blaster) - Shoots 6 bullets in spurts, has the same fire-rate as a shotgun (Inspired by Celeste)
Snowball Launcher (Railgun) - Shoots a massive snowball (BFG bullet) at high speeds. Note that this does not have the BFG laser tracker thing that the normal bullet has. (Inspired by Celeste)
Seeker (BFG) - Acts as an aggressive sentry. Does not move once fired, but if an enemy or group of enemies approach it, they will be obliterated by the bullet(s). (Inspired by Celeste)
Rocket Jumper (Rocket Launcher) - No longer does any damage, meaning it also doesn't do any damage to the player. As a result, you can use this to rocket jump great distances. (Inspired by TF2)
Crystal Shotgun (Grenade Launcher) - Shoots 4 small damaging grenades along with a railgun blast.

The other weapons were slightly modified to have more bullets or firepower or left untouched since I didn't feel that they needed to be changed that much to fit the mod. 

### Objective

With all these new abilities and weapon changes, your primary goal is to beat levels as quickly as possible. 
The levels you beat have their times saved permanently into 'records.txt' with their associated map.
To view your records, either press F7 or type into the console 'records'. 

### New UI elements

Stamina: The amount of air time you can get from the new abilities are limited, so you can get exhausted from stamina. You have 10 stamina in total, and to regain it you have to touch the ground again (similar to Celeste). 
Dash: An indicator of whether or not your dash is on cooldown. 
Speed: This is the absolute value of how fast you're going.
Time: A timer counting in seconds since the beginning of the level. You can use this to track how much time you're spending on a level. 


## Deliverables

Add in 5 movement abilities

Change the weapons to fit Celeste

Add a timer and keep track of player completion times (file ops)

~~Add in collectibles~~ (INCOMPLETE)

Add stamina management
