Asunder
=======

This project is a modified version of MC_Pitman's [Biome Bundle](https://sites.google.com/site/biomebundle/) that generates only floating islands. Like Biome Bundle, this project is intended for use with the Minecraft plugin [TerrainControl](https://github.com/MCTCP/TerrainControl). It includes a copy of [Archipelago](https://github.com/EmptyStar/Archipelago) that is used to create the islands.

Installation
------------

This project contains both custom biomes and custom objects that must be copied to their respective locations for your world. The [CustomBiomes folder](https://github.com/EmptyStar/Asunder/blob/master/CustomBiomes) should replace the CustomBiomes folder of your world, and the [CustomObjects folder](https://github.com/EmptyStar/Asunder/blob/master/CustomObjects) should replace the CustomObjects folder of your world. Note that copying the folders in their entirety will overwrite any existing biomes and objects for your world, so be careful not to overwrite any existing files or folders that may contain data that you want to preserve. If you must preserve existing biomes or objects, then you may want to copy items from Asunder to your world folders individually.

Terrain
-------

The terrain generated with this project will consist solely of floating islands, floating shards of land, and any other small features defined by Biome Bundle such as houses and ruins. Larger islands spawn at low elevations while smaller islands spawn at higher elevations. The terrain contains no ocean and no bedrock; the bottom of the world is open to [The Void](http://minecraft.gamepedia.com/The_Void).

Note that because of the islands spawned at higher elevations, generating terrain using Asunder in a normal world may cause severe performance issues similar to Minecraft's own [Amplified](http://minecraft.gamepedia.com/Amplified) setting. Performance is greatly improved when the terrain is generated in either the End or Nether dimensions. Another method to improve performance is to modify the island classes in the [included Archipelago installation](https://github.com/EmptyStar/Asunder/blob/master/WorldObjects/Archipelago) to spawn at lower elevations.

Known Issues
------------

Known issues for the current version of Asunder are listed below.

 * Islands may overlap in strange configurations

If you would like to contribute fixes for any of these issues, pull requests are welcome. For any reported issues, screenshots and the output of the `/tc biome` command would be extremely helpful.

License and Authors
-------------------

Created by EmptyStar. Original works by MC_Pitman remain in this project and are permitted under [Biome Bundle's license](https://github.com/BiomeBundle/BiomeBundle/blob/master/license). Asunder is licensed MIT. See [LICENSE](https://github.com/EmptyStar/Asunder/blob/master/LICENSE) for details.
