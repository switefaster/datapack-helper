# datapack-helper
VSCode datapack-helper extension, providing basic template for datapack creation and autocomplete for command functions.

Some data used are from [Minecraft data](https://github.com/PepijnMC/Minecraft).

## Usage
### Commands
```
datapack.initialize
```
Initialize a datapack, generate `.datapack` folter and files for tracking data, and `pack.mcmeta`.

```
datapack.read
```
Parse functions and advancements, prepare completion data and store them in `.datapack` folder.
### Files
```
├ .datapack
├────── advancements.json   Advancement data, would be generated by using datapack.read command.
├────── entity_tags.json    Entity tags (/tag command) data, containing list of tags.
│                           NEEDS TO BE ENTERED BY THE USER.
├────── teams.json          Teams data, containing list of teams.
│                           NEEDS TO BE ENTERED BY THE USER.
├────── sounds.json         Sounds.json.
├────── functions.json      Function data, would be generated by using datapack.read command.
└────── objectives.json     Scoreboard objectives data, would be generated by using datapack.read command.
```
