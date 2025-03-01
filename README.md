# Pokémon Red and Blue Mirror Match Hack

This is Pokémon Red and Blue rom hack based on the awesome dissasembly project [pokered](https://github.com/pret/pokered). Simply, the hack forces every trainer battle to be a mirror match by copying the opponents party to yours.

It builds the following ROMs:

- pokered.gbc `sha1: ea9bcae617fdf159b045185467ae58b2e4a48b9a`
- pokeblue.gbc `sha1: d7037c83e1ae5b39bde3c30787637ba1d4c48ce2`
- pokeblue_debug.gbc (debug build) `sha1: 5b1456177671b79b263c614ea0e7cc9ac542e9c4`

## Patching an existing ROM
If you already have an existing US red/blue rom backup, you can use a tool like Lunar IPS to apply the patches found in [Releases](https://github.com/KahunaMC/pokered-mirrormatch/releases). There is a good guide on how to patch ROMs on [Pokecommunity.com](https://www.pokecommunity.com/showthread.php?t=333151)

***Disclaimer: These release files are **NOT** red/blue roms, they are simply binary patches of the changes made here. I will **NOT** help you find ROMs. You should use a legally obtained ROM that you dumped from your own cartridge. ***

## Compiling from source
For information on how to compile the code into a working ROM, see [**INSTALL.md**](INSTALL.md).

## Known issues
- Sometimes trainers have missing PP for their moves when coppied. Notably Brocks Onix has no PP for Bide. This isn't a limitation of the hack, but classic Gen1 jank. Since trainers in Gen1 don't use PP during battle, this was sometimes left out of their data. I am leaving this as is for that authentic Gen1 jank feel. Feel free to fix the data tables for trainers when you compile the ROM.
- It is very easy to get softlocked while using this hack. It is recommended that you always have a way to get out of areas that require special moves like cut and surf. As an example you need cut to fight Lt. Surge, but you will be walking out with his party of electric Pokémon.

## Resources
- [GB Assembly Guide](https://eldred.fr/gb-asm-tutorial/index.html) - A great guide on the Gameboy Assembly Lanauge, including a lot of tricks and traps that you can run into
- [Another GB Programming Guide](https://fms.komkon.org/GameBoy/Tech/Software.html) - A similar resource to the last one. 
- [Romhacking.net: Pokémon Memory Map](http://datacrystal.romhacking.net/wiki/Pok%C3%A9mon_Red/Blue:RAM_map) - A great resource for knowing which memory addresses point to what in pokemon's ROM
- [Bulbapedia: Gen 1 Pokémon Party Structure](https://bulbapedia.bulbagarden.net/wiki/Pok%C3%A9mon_data_structure_(Generation_I)) - A great resource on the structure of the party data in pokemon
- [Bulbapedia: Gen 1 Pokémon Indexes](https://bulbapedia.bulbagarden.net/wiki/List_of_Pok%C3%A9mon_by_index_number_(Generation_I)) - List of Gen1 pokemon by index number
- [Sameboy/Debugger](https://sameboy.github.io/debugger/) - Sameboy is a general purpose gameboy emulator that I used for testing. It's debugger were great for looking at the memory of the game while it was running
- [CyberChef](https://gchq.github.io/CyberChef/) - Used to convert GB text into ASCII for debugging. (Convert from hex, Sub 63 decimal)

## See also

Other dissasembly projects by the team that made [pokered](https://github.com/pret/pokered).

- [**Pokémon Yellow**][pokeyellow]
- [**Pokémon Gold/Silver**][pokegold]
- [**Pokémon Crystal**][pokecrystal]
- [**Pokémon Pinball**][pokepinball]
- [**Pokémon TCG**][poketcg]
- [**Pokémon Ruby**][pokeruby]
- [**Pokémon FireRed**][pokefirered]
- [**Pokémon Emerald**][pokeemerald]

[pokered]: https://github.com/pret/pokered
[pokeyellow]: https://github.com/pret/pokeyellow
[pokegold]: https://github.com/pret/pokegold
[pokecrystal]: https://github.com/pret/pokecrystal
[pokepinball]: https://github.com/pret/pokepinball
[poketcg]: https://github.com/pret/poketcg
[pokeruby]: https://github.com/pret/pokeruby
[pokefirered]: https://github.com/pret/pokefirered
[pokeemerald]: https://github.com/pret/pokeemerald
