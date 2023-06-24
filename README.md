# msk_bansystem
[STANDALONE] Simple Ban System

## Description
* Simple Ban System
* Admin Commands
* Exports
* Discord Logs

## Exports
`source` can be set to `nil` if you execute it from another resource and not using a Command.

**Ban**
```lua
exports.msk_bansystem:banPlayer(source, targetId, time, reason)
```
**Unban**
```lua
exports.msk_bansystem:unbanPlayer(source, banId)
```
**IsPlayerBanned**
```lua
exports.msk_bansystem:IsPlayerBanned(targetId)
```

## Requirements
* [msk_core](https://github.com/MSK-Scripts/msk_core)
* [oxmysql](https://github.com/overextended/oxmysql)