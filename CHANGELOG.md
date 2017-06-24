Changelog
=========

This file contains information about changes made in each version of this project.

v1.2
----

 * Added workaround for flowing liquids which eliminates the need for command blocks
 * Removed liquid BO3 and NBT files which are no longer needed
 * Increased the frequency of floating fragments
 * Made all ores more common
 * Moved "useful" `Ore` and `Vein` resources (coal, iron, diamond, etc.) to the bottom of the resource queue in order to make them more common on the terrain's surface
 * Removed all `(AIR,WATER,*,*)` from `ReplacedBlocks` settings (which mostly affects river biomes)

v1.1
----

 * Added WorldConfig.ini

v1.0
----

 * The base Biome Bundle has been updated to the latest TerrainControl version
 * Sweeping changes to all biomes
 * Surface blocks are more varied
 * Less grass/flowers/etc. spawn on blocks they shouldn't
 * All `Grass` resources have been replaced with `Plant` resources
 * Some unappealing BO3's have been removed from the biomes
 * Some missing `CustomStructure` resources have been added
 * River biomes have been removed from other biome configurations (though the river biomes themselves still exist)
 * Liquids are replaced with command blocks to mitigate a TerrainControl bug that prevents liquid sources from flowing
 * The included [Archipelago](https://github.com/EmptyStar/Archipelago) installation has been updated to v1.0
 * Updated README.md

v0.1
----

 * Initial release
