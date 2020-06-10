# CharacterReset2
Lets players manually reset their character back to the server's SSC default character. This plugin is branched out from CustomStarterItems to only reset the character as TShock has included starter items into itself. (originally made by Bippity)

[Character Reset [SSC]](https://tshock.co/xf/index.php?resources/character-reset-ssc.4/)

**TShock version:** 4.4.0 pre-11

**API version:** 2.1

Character Reset plugin originally by [Bippity](https://github.com/bippity/CharacterReset), updated by me.

## How to install
1. Put the .dll file into the ServerPlugins folder
2. Grant your desired group the necessary permissions to use this plugin
3. Done!

### Permissions
- `character.reset.stats `
  - Needed to use `/resetcharacter` and its parameters
- `character.reset.inventory`
  - Needed to use `/resetcharacter` and its parameters
- `character.reset.quests` 
  - Needed to use `/resetcharacter` and its parameters
- `character.reset.player`
  - Needed to use `/resetplayer` and its parameters
- `character.reset.players`
  - Needed to use `/resetplayers` and its parameters

## How to use
### Commands
`< >` indicates a parameter that must be entered for the command to work, while `[ ]` indicates an optional parameter. `|` means OR. You must surround your parameter (player name or item name) with `" "` if it contains spaces. If you want to reset an offline player, the name you enter must be exact and case sensitive.
- `/resetcharacter <all|stats|inventory|quests|banks>`
 - Reset the player's own character
- `/resetplayer <username> <all|stats|inventory|quests>`
 - Reset another player's character data
- `/resetplayers <all|stats|inventory|quests>`
 - Reset all players' character data
 
### Parameters
- `all`
 - Resets everything, use this with caution.
- `stats`
 - Resets HP and MP.
- `inventory`
 - Resets inventory.
- `quests`
 - Resets Angler fishing quests.
- `banks`
 - Resets all four banks.

## Examples 
- Reset your own fishing quests
  - `/resetcharacter quests`
- Reset moisterrific's inventory while she's offline
  - `/resetplayer moisterrific inventory`
- Reset all players' SSC data to start a fresh survival
  - `/resetplayers all`
