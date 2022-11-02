#ProjectMod_FinalV

***Common Deliverables:***
1. A Desktop Shortcut to automatically launch your mod.
   - *(Completed)*
2. A README.md file in your Github repository explaining:
   - What your mod is;
   - What has been changed; and
   - How to test each deliverable.
   - *(Completed)*
3. A Modified Main Menu.
   - *(Completed - I would've like to fix Start Game button, but Main Menu is Modified)*
4. A Modified Heads-Up Display (HUD) to reflect a key feature of your mod.
   - *(Completed - I would've liked to improve upon this and make the HUD modification that results from interacting with a powerup to persistent longer like Quad Damage's HUD)*
5. An In-Game Help Screen explaining your mod changes.
   - *(Completed)*

***My Specific Deliverables:***
1. Rhythm-based bonuses (The timer that affects gunplay/damage).
   - *(Unfinished)*
2. Enemies spawning in waves.
   - *(Unfinished)*
3. 5 NPCS that can be summoned and taken over (Monsters that you play as).
   - *(Unfinished)*
4. 5 Custom Pick-ups/Powerups.
   - *(Unfinished - This deliverable has the most progress, but falls short of actual functionality)*
5. Change enemy behavior (Of human NPCs) to the music / Give 5 enemies (Human NPCs) abilities.
   - *(Unfinished)*

***README.md Explanations***
- What is my mod?
  - My mod was intended to be a Hordes Mode type game where the player would have to survive waves of enemies. There were a few twists for my project. First, the enemies would be human NPCs and the player would ally themselves with the Strogg. Second, the player would have the ability to shoot a special gun at their Strogg allies and swap bodies (or in a game sense, swap stat values to avoid dying). Third, the game would run at a set rhythm where the player would do more damage based on how close their gunshots matched the tempo (to prevent spray and pray). However, many of my specific deliverables ended up falling flat, so my mod doesn't live up to it's original intentions. In it's current form, it's a collection of half-working powerups.
- What has been changed?
  - My mod makes huge changes to the Main Menu and minor changes to the HUD when interacting with incomplete powerup objects.
- How to test each deliverable?
  - To test the shortcut, open [Quake 4 - ProjectMod.lnk].
  - To test the main menu, open [Quake 4 - ProjectMod.lnk] and peruse the main menu. The primary color of the main menu has been changed to red and an entirely new hidden button was added (below settings). Click on that button to access a specific page for the mod. The Start Game button doesn't work, but the Mod Help (Forward), Mod Help (Back), and Back button all work. Click (Forward) to go to Help Page 2/2 and (Back) to go to Help Page 1/2. Click Back to go back to the main menu.
  - To test the HUD, run the CMD [map mp/q4dm5] (the actual map doesn't matter, but this is the one I've been using). Once you are in the map, run the CMD [spawn powerup_] followed by either: [aim_assist], [gold_star], [fall_boots], [jump_boost], or [tiny_potion]. For instance, when [spawn powerup_aim_assist] is used, a powerup will spawn on the map and picking up that powerup will allow a TGA image to appear on the HUD.
  - To test the help menu (this step is best completed after testing the HUD), press the pause button. From here, the changes made to main menu will still be present. Thus, the hidden button underneath settings can still be clicked. From here, the Mod Help (Forward) and Mode Help (Back) buttons can be used to interact with all pages of the Help Screen. Granted, there isn't much to explain in terms of the mod since most of the specific deliverables ended on not working.
  - Out of all 5 deliverables, only 1 is worth testing: the powerups. To test the powerups (although they don't give any effects), refer to HUD testing section where CMD [spawn powerup_] followed by the five options is used to spawn one of my custom powerups.



*These files are stored in C:\Program Files (x86)\Steam\steamapps\common\Quake 4\ProjectMod*
