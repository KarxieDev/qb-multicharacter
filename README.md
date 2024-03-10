# qb-multicharacter
Multi Character Feature for QB-Core Framework :people_holding_hands:

Added support for setting default number of characters per player per Rockstar license


## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-spawn](https://github.com/qbcore-framework/qb-spawn) - Spawn selector
- [qb-apartments](https://github.com/qbcore-framework/qb-apartments) - For giving the player a apartment after creating a character.
- [qb-clothing](https://github.com/qbcore-framework/qb-clothing) - For the character creation and saving outfits. 
- [qb-weathersync](https://github.com/qbcore-framework/qb-weathersync) - For adjusting the weather while player is creating a character.

Can also be used with ST4LTH's reskins
- [qb-clothing](https://github.com/ST4LTH/qb-clothing)

## Screenshots
![Character Selection](https://cdn.discordapp.com/attachments/1194309035483213874/1216371820127719515/image.png?ex=66002589&is=65edb089&hm=ef838e7c46ddae66062e60f085615ce5e8545eefb239a568c65ed5e0c3b5e2ba&)

## Features
- Ability to create up to 4 characters and delete any character.
- Ability to see character information during selection.

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure qb-core
ensure qb-multicharacter
ensure qb-spawn
ensure qb-apartments
ensure qb-clothing
ensure qb-weathersync
```
## Credits
- [ST4LTH Base Multichar](https://github.com/ST4LTH/qb-multicharacter)
