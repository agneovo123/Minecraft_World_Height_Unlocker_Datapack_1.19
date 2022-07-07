# Minecraft World Height Unlocker Datapack 1.19
Increases the build limit in
- The overworld from -64 to 320 --> -512 to 1024
- The nether from 0 to 256 --> -512 to 1024
- The end from 0 to 256 --> -512 to 1024

does NOT increase world generation height, only the build limit.

You can change the heights by going into the .zip\data\minecraft\dimension_type\
and in the .json files changing the 
  "min_y": -512,
  "height": 1536,
  "logical_height": 1536,
values
  "min_y": -512, is the bottom of the world
  
  "height": 1536, AND "logical_height": 1536, define the top of the world in this example as 1024 because:
  "min_y" + "height" = -512 + 1536 = 1024

"monster_spawn_light_level" and "monster_spawn_block_light_limit" are probably not the right values for the nether
