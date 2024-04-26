## Description
This is a mod that provides several collections of icons matching the game's UI style for modders to use in their mods.   This means that modders don't have to waste time finding or re-creating icons, or manually loading them into the game's UI.

This doesn't do anything unless you have a mod that uses it, in which case it's required.

The icons themselves have been specially crafted by Chameleon TBN to blend in seamlessly with the game.

## Modders
All icons are automatically pre-injected into the game's UI and are accessible via coui://uil/StyleName/IconName.  Typically, this would form the `src` attribute of a relevant UI element (e.g. `src="coui://uil/Standard/ArrowLeft.svg"`).

The most up-to-date and complete information on what icons are included can be found on the README of the GitHub page.

### Styles
The initial styles are Standard (matches the game UI), Dark (dark theme), and Colored (more colorful versions).  Requests for new styles are welcome!

### Colored icons
Modders can change the color of all color icons by using the layer color IDs in css:
- black
- white
- grey
- brown
- violet
- red
- orange
- yellow
- green
- blue

Additionally you can use the color # codes to change the look. As there's only one defined color palette this should work similar smooth.


### Support
I'm available for direct contact on the Cities: Skylines modding discord, including for tailored advice for your specific situation - as always, I'm happy to help out any modders, new or old! 
