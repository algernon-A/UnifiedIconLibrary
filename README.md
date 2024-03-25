## Unified Icon Library.
A mod for Cities: Skylines 2.  Available for download only on [Paradox Mods](https://mods.paradoxplaza.com/mods/74417/Windows).

The primary platform for support is the [Cities Skylines Modding Discord](https://discord.gg/HTav7ARPs2).

### Description
This is a mod that provides several collections of icons matching the game's UI style for modders to use in their mods.   This means that modders don't have to waste time finding or re-creating icons, or manually loading them into the game's UI.

This doesn't do anything unless you have a mod that uses it, in which case it's required.

### Modders

All icons are automatically pre-injected into the game's UI and are accessible via coui://uil/StyleName/IconName.  Typically, this would form the `src` attribute of a relevant UI element (e.g. `src="coui://Standard/ArrowLeft.svg"`).

The initial styles are Standard (matches the game UI), Dark (dark theme), and Colored (more colorful versions).  Requests for new styles are welcome!

The full list of icons and themes can be seen in the [`Icons` directory of this repository](https://github.com/algernon-A/UnifiedIconLibrary/tree/master/Icons).
