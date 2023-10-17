# mrtaufner-quake-maps
My maps, prepackaged and ready to play (except for [AD](https://www.moddb.com/mods/arcane-dimensions/downloads/arcane-dimensions-180-with-patch-1), because it is too large).

Mod credits:
SMP (speed mapping progs): David "dumptruck_ds" Spell et al
Copper: Matthew 'Lunaran' Breit
Arcane Dimensions: Simon O' Callaghan et al

## Choose your fight... erm... source port)
As mentioned above, these maps are ready to play but most of them will require a modern source port to play and the original game files as a base.
I personally recommend [Ironwail](https://github.com/andrei-drexler/ironwail/tags), but any of the following will do just fine:

- [QuakeSpasm](https://sourceforge.net/projects/quakespasm/)
- [QuakeSpasm Spiked](https://triptohell.info/moodles/qss/)8
- [vkQuake](https://github.com/Novum/vkQuake/tags)
- [RetroQuad](https://www.patreon.com/mankrip) (you're a real one if you know this)
- [JoeQuake](http://joequake.runecentral.com/downloads.html)
- [FTE](https://fte.triptohell.info)

Each of these has its own pros and cons but all of them will get the job done. However, I only know the commands for Ironwail and QuakeSpasm.

## How to play
Considering you have an original Quake copy, be it a cd release or the digital version, then just copy your id1 folder to the same folder
where your source port .exe is. You can also do it the other way around: copy the contents from the source port .zip and paste it over your 
Quake 1 installation.

Now you're ready to run the game, and open the console (QuakeSpasm does this by default) with the tilde key (the key right above Tab).

1. type `game xxxxx` then press enter and you'll load specified mod. Some source ports have a directory navigator so maybe you won't need to do this step.
2. type `map xxxxx` then press enter and you'll load the specified map. Note that you can play vanilla maps with mods doing this too.

Anyway I'll specify all the steps and commands needed to play any of the maps included here. Tab can be used for autocomplete

### Coffee Quake 2 (id1)
1. Copy the files in the `maps` folder from `CQ2_mrtaufner`
2. Paste it in `id1/maps`
3. Start the game and open the console
4. type `map e1_mrtaufner` or `map e2_mrtaufner`

### Quake Brutalist Jam
1. Copy `QBJ_mrtaufner` on the same folder containing the `id1` folder and the source port .exe.
2. Start the game and type `game qbj_mrtaufner`. The Copper mod should be now loaded
3. Type `map qbj_mrtaufner`

### Speedmapping 214 - Prototypes 2
1. Copy `SM214_mrtaufner` on the same folder containing the `id1` folder and the source port .exe.
2. Start the game and type `game sm214_mrtaufner`. The SMP mod should be now loaded
3. Type `map sm214_mrtaufner`

### Speedmapping 220 - Prototypes 3
1. Copy `sm220_mrtaufner` on the same folder containing the `id1` folder and the source port .exe.
2. Start the game and type `game sm220_mrtaufner`. The SMP mod should be now loaded
3. Type `map sm220_mrtaufner`

### Speedmapping 221 - Bridges
1. Copy `sm221_mrtaufner` on the same folder containing the `id1` folder and the source port .exe.
2. Start the game and type `game sm221_mrtaufner`. The SMP mod should be now loaded
3. Type `map sm221_mrtaufner`

### Speedmapping 224 - Protypes 4
1. Copy `sm224_mrtaufner` on the same folder containing the `id1` folder and the source port .exe.
2. Start the game and type `game sm224_mrtaufner`. The SMP mod should be now loaded
3. Type `map sm224_mrtaufner`

### Xmas Jam 21
1. Download [Arcane Dimensions](https://www.moddb.com/mods/arcane-dimensions/downloads/arcane-dimensions-180-with-patch-1)
2. Unzip the mod in a folder named `ad` (can be named whatever) at the same level as the `id1` folder and the source port .exe.
3. Copy the contents from `XmasJam21_mrtfradyang` (`gfx`, `maps` and `particles`. `mapsrc` and the .txt file is optional) to the `ad` folder
4. Start the game and type `game ad`
5. Type `map xmj21_mrtfradyang`
