# Free Minecraft PvP/Faction Server Template

Simple Minecraft PvP Faction server template to start a faction server.

* Factions
* Scoreboard
* Spawn with portals
* Shop
* Anti-cheat
* Preconfigure permissions

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

### Spawn

A spawn world is preconfigured in this minecraft server template which containt:

* NPC Shop
* NPC Menu
* Portals

## Permissions

LuckPerms is included with this preconfigured groups/permissions:

* Owner (owner)
* Admin (admin)
* Moderator (mod)
* VIP (vip)
* Player (player)
* Default (default permission group)

When a player create or join faction, the rank change from `default` group to `player` group.

To add full rights to an user:

```
lp user <username> parent add owner
```

To remove an user from the owner group:

```
lp user <username> parent remove owner
```
