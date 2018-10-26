# video-game-hacks
## Purpose
This is just a repo used for publishing/archiving my past work on hacking video games. The codes work, but there is no guarantee it won't be patched. A lot of work published here will be for games that are already shutdown or are no longer popular for obvious reasons. Sometimes there will be more instructions/readme available to explain what something does.
## Resources
1. A playlist of the few recordings I actually saved throughout the years https://www.youtube.com/playlist?list=PLXSXKjpE2HLaxez5QLiSUVHgSq3CScEfx many were lost due to hard drive failures and lack of storage back in the poor student days
## Games
### World of Tanks
Coming soon...
### SD Gundam Capsule Fighers Online (SDGO)
#### Exploits
1. Full map vac for mission stages
2. Infinite ammo/booster/one-hit KO
3. Automate unit movement using built-in scripting engine's bot AI
4. Complete M16 Taozi mission in the fastest time possible without triggering disconnect by waiting for the in-game timer
5. 100% configurable using AI_Config.txt
6. Injects loader into game files to allow loading external modules to easily test new code changes
### Luna Online
#### Exploits
1. Full map AOE via memory editing before the official resource management tool got leaked
2. Enter/Exit PvP mode freely without restrictions
3. Bypass resource modification check that was later implemented after the official tools got leaked
4. Perfect fishing by modifying the fishing slider
5. Bypass any prerequisites required to use some skills, most notable being the theif's backstab skill that required cloaking
### Ghost Online
1. Full map VAC that easily got patched as it was super easy to do back when the game was first launched
2. Full map hitbox, a collab with a fellow hacker centered around the idea that there are different hitboxes depending on which weapon was equipped. This allowed for hitting any monster on the map without moving
3. Full map looting, this is very similar to the hitbox concept, there is also a range available that determines if you can loot the item or not
4. Constant attacks on the move, you can actually see this being used in that one video I have on all the hacks that were available. This one was easier than it looks. The game stops the character from being able to move if it thinks its attacking. By making it look like the character is always standing, you can attack in fast repetition. This combined with another exploit that lets you automatically attack helped create this exploit
5. Removing name validation during character creation. This is probably rare now, but back in the day a lot of games never had any server-side validation. GO didn't have any validation for valid character names on the server-side. This made it very easy to modify the client and create characters with any names imaginable
6. Unbannable characters - this goes hand-in-hand with the name validation removal, for some reason the only way a GM can ban a player is by typing `/ban player_name`. This command doesn't work when you have spaces and other special characters like `/` in your name. Great design right?
### MapleStory
#### Exploits
1. Full map server-side or client-side Mouse VAC. This included the first iterations where server-side still worked, as well as client-side mouse-vac that worked around the range limitation by teleporting the character to other areas of the map when mob count is low
2. Explode any item for Bandit's Meso Explosion. The idea came to me back when Bandits were first released, it was a lot of fun to find out what checked the item on the ground to see if it was Mesos or not, had a lot of fun exploding Zakum for free using snail shells till someone else found the same exploit and leaked it for them to patch
3. Many other hacks back in the early 2000s that I can no longer remember. A lot of good collaboration that went on with other hackers in the scene
## TO-DO
1. Locate other SDGO related hacks such as removing all walls from map files to allow for full map wallhack
2. Describe thought process and concept used for exploiting past video games where I no longer have any data for
