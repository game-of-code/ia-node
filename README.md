# CREATE A NEW GAME

```
npm run create [GAME_NAME] [CHARACTER] [PLAYER_NAME] [VERSUS_PLAYER]

```
* GAME_NAME: Name of the new game
* CHARACTER: Type of character (WARRIOR, PALADIN, DRUID, SORCERER, ELF, TROLL)
* PLAYER_NAME: Your name
* VERSUS_PLAYER: If true, an other player can join your game else it's an IA

## If behind a proxy, prepend the command with :

http_proxy="YOURPROXY" https_proxy="YOURPROXY" npm run ...

# JOIN A GAME

```
npm run join [GAME_TOKEN] [CHARACTER] [PLAYER_NAME]

```
* GAME_TOKEN: Key of the game you want to join
* CHARACTER: Type of character (WARRIOR, PALADIN, DRUID, SORCERER, ELF, TROLL)
* PLAYER_NAME: Your name
