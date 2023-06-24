# msk_bansystem
[STANDALONE] Simple Ban System

## Description
* Simple Ban System
* Admin Commands
* Exports
* Discord Logs

## Commands
You can set the following Statements for Time:
* M for minute
* H for hour
* D for day
* W for week
* P for permanent

**Ban**
`/ban playerID time reason`
Example: `/ban 1 1H 'Banned for Cheating'` *1 Hour Ban*
Example: `/ban 1 P 'Banned for Cheating'` *Permanent Ban*

**Unban**
`/unban banID`
Example: `/unban 1`

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