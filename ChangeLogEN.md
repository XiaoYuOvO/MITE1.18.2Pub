# v0.1.0-beta Change Log
## World Generation
* Now you can only choose Amplification or Giant Biome when creating the world
* The structures will only be generated after the player unlocks a certain advancement
* Removed the gravel deposits on the bottom of the lake and river
* Animals will regenerate every 128 days 
## Blocks
* Make gravel and sand affected by gravity
* Added furnaces of various levels (clay furnace, hardened clay furnace, stone furnace, obsidian furnace, netherrack furnace)
* Added various levels of workbenches
* Destroying leaves has a chance to get sticks
* The furnace can be harvested by hand
* Harvesting gravels will drop flint, flint shards, and other metal nuggets and shards. The drop probability is shown in the following table:

Item| Chance
------------ | -------------
Gravel（Itself） |3/4 
Flint shard |5/32 
Copper nugget |1/18 
Silver nugget |1/54 
Flint |1/96 
Gold nugget |1/162 
Obsidian shard |1/486 
Emerald shard |1/1458 
Diamond shard |1/4374 
Mithril shard |1/13122 
Adamantium shard |1/26244 

## Game mechanics
* Now it takes time to craft items, and the workbench must have enough level
* Players cannot now mine blocks that have not reached the mining level
* When the player is born, the max health and max saturation are 6 points, and each level increases by 2 points, up to 20 points
* Upgrade requires higher experience points:\
            Set level = `n`;Experience required for each level = `10 ( n + 1 )`;Total experience per level = `5n² + 15n`
* Player drops 1/3 of the experience before death, if there is no level, it will drop to a negative number
* Players cannot quickly regenerate their health when they are full, but as long as they have saturation,\ 
  they can regenerate 1 point of health every 64 seconds.\
  When lying in bed, they can restore 1 point every 32 seconds.
* Hunger speed increased by 1.25 times
* Players can sprint as long as the player have hunger or saturated,
* Reduced the player's radius of reach (2.8 blocks for blocks, 1.75 blocks for entities[when empty-handed])
## Items
#### Foods
* Added salad,eat to give 1 hunger point after eating
* Make wheat seeds edible and give 0.3 saturation point
* Apple's hunger point reduced to 1 point
* Make brown and red mushrooms edible, give 1 hunger point and 0.1 saturation point\
  However, eating red mushrooms will give the player poison effect for 10s and nausea effect for 60s.
#### Tools and weapons
* Added tools,fishing rods and weapons of various metals
* Tools and weapons can provide players with a radius of reach bonus
## Anti-cheat
* When creating a world, you cannot choose the creative mode and cheat, nor can you choose data packs, bonus chests, and game rules
* Unable to choose game mode and cheat when share to LAN
* The brightness is locked at darkness and cannot be modified
* Difficulty is locked to hard
## GUI
* The world selection interface will only display the supported worlds (the world created by MITE 1.16.1)
* Players can't see the coordinates and the block or fluid facing at in Debug GUI