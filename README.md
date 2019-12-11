# Free Minecraft PvP/Faction Server Template

Simple PvP Faction template to start your faction server.

![Spawn](/spawn.png)

* Factions
* Scoreboard
* Spawn with portals
* Shop
* Anti-cheat
* Preconfigured permissions

Feel free to contribute ;)

Sponsor: [mTxServ - Minecraft Server Hosting](https://mtxserv.com/host-server/minecraft)

## Requirements

* Tested on Paper 1.14
* Compatible Spigot 1.14, Paper 1.14

## Plugins Pack

* Factions
* BossShopPro
* WorldEdit
* WorldGuard
* IllegalStack
* ProtocolLib
* ChestCommands
* Citizens
* Citizens CMD
* CombatLogX
* CoolDamageIndicators
* Essentials
* Essentials Chat
* Essentials Spawn
* HolographicDisplays
* Multiverse
* Multiverse NetherPortals
* Multiverse Portals
* Rankup
* [LuckPerms](https://www.spigotmc.org/resources/luckperms-an-advanced-permissions-plugin.28140/)
* [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/)
* [Vault](https://dev.bukkit.org/projects/vault)
* [Matrix AntiCheat](https://www.spigotmc.org/resources/matrix-anticheat-advanced-cheat-detection-1-8-1-12-1-13-1-14.64635/)

## Worlds

Add in the `server.properties` file:

```
level-name=Factions
```

To generate the `mine` world, use mv command, for example:

```
/mv create mine normal
```

### Spawn

The Spawn world provided in the template contains:

* NPC Shop
* NPC Menu
* Portals

### Factions

Add your own faction world. This name must be `Factions` to successively works, else your portals (in the spawn) will not work.

### Mine

Add your own mine world. This name must be `mine` to successively works, else your portals (in the spawn) will not work.

## Permissions

LuckPerms is included with this preconfigured groups/permissions:

* Owner (owner)
* Admin (admin)
* Moderator (mod)
* VIP (vip)
* Player (player)
* Default (default permission group)

When a player create or join a faction, this rank change from `default` group to `player` group.

To add full rights to a user:

```
lp user <username> parent add owner
```

To remove a user from the owner group:

```
lp user <username> parent remove owner
```

## Usefull commands

* `/spawn`
* `/shop`
* `/menu`
* `/home`
* `/rules`
* `/f`
