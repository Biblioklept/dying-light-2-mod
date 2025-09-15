# Dying Light 2 Mod
A Dying Light mod merge that tweaks gameplay to the way that I prefer it.

## Important Notice
Mod merge is provided as is. If errors occur please report to this GitHub page instead of the mod authors.

### Data2 - Mods Included
Version that is much more to my preference but is dependent on RGB's Enhanced Vanilla Modpack updates.

- [Disable Telemetry](https://www.nexusmods.com/dyinglight2/mods/20)
- [No Post Processing](https://www.nexusmods.com/dyinglight2/mods/31)
- [RGB's Enhanced Vanilla Modpack](https://www.nexusmods.com/dyinglight2/mods/1729)
	- Removed lockpicking bypass from original mod.
	- Removed durability degradation.
	- Increased day experience to 2x and night experience to 4x.

### Data3 - Mods Included
Version that is easier to patch but not the main version. Very vanilla friendly.

- [Disable Telemetry](https://www.nexusmods.com/dyinglight2/mods/20)
- [No Post Processing](https://www.nexusmods.com/dyinglight2/mods/31)
- [Infinite AIO - Lite]()
- 2x Day XP + 4x Night XP.
	- Modifies scripts/player/player_variables.scr  
	Param("OpenWorldXPModifier", "2.0");  
	Param("OpenWorldNightXPModifier", "4.0");
- No Durability Degradation
	- Modifies scripts/player/player_variables*.scr  
	Param("MeleeWpnDurabilityMulReduce", "0.0");
	- Modifies scripts/tower_raid/difficulties/tower_raid_player_variables_*.scr  
	Param("MeleeWpnDurabilityMulReduce", "0.0");