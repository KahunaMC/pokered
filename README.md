# Pokémon Red and Blue Mirror Match Hack

This is Pokémon Red and Blue rom hack based on the awesome dissasembly project [pokered](https://github.com/pret/pokered). Simply, the hack forces every trainer battle to be a mirror match by copying the opponents party to yours.

It builds the following ROMs:

- pokered.gbc `sha1: 3a3ab0145027309870e54869f47bece45953ccea`
- pokeblue.gbc `sha1: 98e9a6f708966c187a98f893d15fe9f31e880f5c`
- pokeblue_debug.gbc (debug build) `sha1: fa475878aafb5c1e8f3e242affa12e14bc35efdd`

To set up the repository, see [**INSTALL.md**](INSTALL.md).

## Known issues
- Sometimes trainers have missing PP for their moves when coppied. Notably Brocks Onix has no PP for Bide. This isn't a limitation of the hack, but classic Gen1 jank. Since trainers in Gen1 don't use PP during battle, this was sometimes left out of their data. I am leaving this as is for that authentic Gen1 jank feel. Feel free to fix the data tables for trainers when you compile the ROM.
- It is very easy to get softlocked while using this hack. It is recommended that you always have a way to get out of areas that require special moves like cut and surf. As an example you need cut to fight Lt. Surge, but you will be walking out with his party of electric Pokémon.

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
