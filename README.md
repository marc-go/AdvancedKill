# Advanced Kill

Minecraft Plugin to kill players with many possibilities

The /kill Command is a littel bit boring, isn't it? But there is the AdvancedKill plugin!
You can kill players with many different methods, for example with an explosion or a lightning.

## Methods:
- anvil - place an anvil above the player
- fall - teleports the player to high 300
- explosion - makes an explosion close to the player
- lightning - summons a lightning above the player
- half - reduces the health of the player to a half heart
- lava - places lava for 3 seconds close to the player
- void - teleports the player into the void
- zombie - spawns a zombie with a diamond sword for 10 seconds next the player

## Usage
```
/akill <method> <player>
```

## Installation
1. Download **AdvancedKill_Paper_x.xx.jar** and copy it into the *plugins* directory from your server.

2. Restart the server

## Filter
The AdvancedKill Plugin has a filter for players. If a player is added to the filter, nobody can kill him with akill.

### Add a player
To add a player, run
```
/afilter <player>
```
### Remove a player
To remoce a player, run
```
/afilter <player>
```

### Turn filter on and off
To turn the filter on and off, open `config.yml`. You can find the config.yml in `plugins/AdvancedKill`
Open it and set `filter-player` to `true`or `false`
