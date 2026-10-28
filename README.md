All modifications require installed BepInEx !

1) BetterDemister.dll
Wisplight now provides x1.7 bigger radius free from magical fog. 

2) BetterMistlandsTerrain.dll
Mystlands terrain becomes more playable, you don't need more jump everytime. There are still rocks and cliffs, but less and you can find a way around it.
I used Mathf.Lerp and Mathf.SmoothStep in Postfix of game metod to gain good numerics for Heightmap. 
*Dry Valleys: Raises lowland height above the water level. No more endless swimming or flooded shores.
*Playable Ridges: Smooths out vertical spike-walls into alpine plateaus using custom curves.
*Natural Soil: Retains micro-roughness under your feet, keeping the terrain naturally bumpy like Meadows.

3) TrophyFix.dll
Fixes dynamic trophy drop chance as it was intended by developers.
Base game chance increases by 5% for every disluck, and after success this bonus drops, back to standart chance. 
Additionally star mobs have stable chance: 1star=30%, 2star=80%
Just fixing bug of latest versions the game.

4) ValheimCharacterBossBuff.dll
*Boss Defeat Rewards: Defeating any boss grants your character a permanent bonus of +8 Max HP and +10 Carry Weight.
*No Buff Farming: Each boss provides a reward only once. You cannot repeatedly farm the same boss to stack infinite stats.
*Character-Bound Progress: Your growth is strictly tied to your specific character. Hard-earned stats will persist across any world or server you join.
*Zero FPS Impact: Calculations and stat updates occur only at the exact moment a boss dies. The rest of the time, the mod stays completely idle.
*Multiplayer Ready: Designed to work seamlessly in multiplayer. The buff is credited to you as long as you are nearby, regardless of who delivers the final blow.

5) ValheimCharacterKeepEffects.dll
fixes a basic vanilla game flaw where all temporary status effects and potion timers are completely wiped whenever you log out or disconnect. With this mod, your current buffs and debuffs are safely remembered and resume exactly where you left off when you rejoin.
*Timer Persistence: Saves the exact remaining duration for Rested, Wet, meads, potions, and skill buffs.
*Vanilla-Safe System: Uses Valheim's internal character dictionary, making it 100% safe to uninstall at any time.
*Server Compatibility: Works on dedicated servers and in multiplayer, running entirely on the client side.
*Smart Filter: Ignores infinite environmental effects.
