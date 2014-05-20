MCBlockFinder
=============

Utility to find clusters of blocks in a MineCraft world.

### World Files
Are located within these directories, respectively:

*Windows*
	
	C:\User\AppData\Roaming\.minecraft\saves\WORLD_NAME\region\
	
*OS X*

	/User/Library/Application Support/minecraft/saves/WORLD_NAME/region/
	
*Linux (Normally)*

	~/.minecraft/saves/WORLD_NAME/region/
	
Region files are made up of **32x32** chunks and each chunck holds **16x256x16** blocks. They are named according to their coodinates e.g. `r.0.0.mca` or `r.-1.-1.mca`.

****

A really useful reference for how minecraft region/Anvil files work can be found [at this blog post][id1] by [Nathan Williams][id2].


[id1]: http://nathanwilliams.github.io/2013/04/16/minecraft-region-files/
[id2]: https://github.com/NathanWilliams