# Admin Commands Reference

Complete list of administrative commands for DPSRP staff.

## Access Levels

| Level | Role | Permissions |
|-------|------|-------------|
| 1 | Moderator | Basic moderation |
| 2 | Admin | Full admin tools |
| 3 | Senior Admin | Management tools |
| 4 | Developer | All access |

## Player Management

### Information
| Command | Usage | Description |
|---------|-------|-------------|
| /checkid | /checkid [id] | View player info |
| /checkname | /checkname [name] | Search by character name |
| /checkcid | /checkcid [citizenid] | Lookup by citizen ID |
| /checkplayers | /checkplayers | List all online players |

### Teleportation
| Command | Usage | Description |
|---------|-------|-------------|
| /goto | /goto [id] | Teleport to player |
| /bring | /bring [id] | Bring player to you |
| /tpm | /tpm | Teleport to marker |
| /setcoords | /setcoords [x] [y] [z] | Teleport to coords |

### Actions
| Command | Usage | Description |
|---------|-------|-------------|
| /kick | /kick [id] [reason] | Kick player |
| /ban | /ban [id] [duration] [reason] | Ban player |
| /unban | /unban [license/steam] | Remove ban |
| /warn | /warn [id] [reason] | Issue warning |
| /freeze | /freeze [id] | Freeze player |
| /unfreeze | /unfreeze [id] | Unfreeze player |

## Economy Commands

| Command | Usage | Description |
|---------|-------|-------------|
| /givemoney | /givemoney [id] [type] [amount] | Give money |
| /setmoney | /setmoney [id] [type] [amount] | Set money |
| /removemoney | /removemoney [id] [type] [amount] | Remove money |
| /checkmoney | /checkmoney [id] | View player finances |

Money types: `cash`, `bank`, `crypto`

## Inventory Commands

| Command | Usage | Description |
|---------|-------|-------------|
| /giveitem | /giveitem [id] [item] [amount] | Give item |
| /removeitem | /removeitem [id] [item] [amount] | Remove item |
| /clearinventory | /clearinventory [id] | Clear all items |
| /openinv | /openinv [id] | View player inventory |

## Job Commands

| Command | Usage | Description |
|---------|-------|-------------|
| /setjob | /setjob [id] [job] [grade] | Set player job |
| /setgang | /setgang [id] [gang] [grade] | Set player gang |
| /firejob | /firejob [id] | Set to unemployed |

## Vehicle Commands

| Command | Usage | Description |
|---------|-------|-------------|
| /car | /car [model] | Spawn vehicle |
| /dv | /dv | Delete nearest vehicle |
| /fix | /fix | Repair current vehicle |
| /setfuel | /setfuel [amount] | Set fuel level |
| /givekeys | /givekeys [id] | Give vehicle keys |

## World Commands

| Command | Usage | Description |
|---------|-------|-------------|
| /time | /time [hour] | Set server time |
| /weather | /weather [type] | Set weather |
| /announce | /announce [message] | Server announcement |

Weather types: `clear`, `clouds`, `rain`, `thunder`, `snow`, `fog`

## Spectate & Monitoring

| Command | Usage | Description |
|---------|-------|-------------|
| /spectate | /spectate [id] | Spectate player |
| /unspectate | /unspectate | Stop spectating |
| /noclip | /noclip | Toggle noclip mode |
| /invisible | /invisible | Toggle invisibility |

## Revive & Health

| Command | Usage | Description |
|---------|-------|-------------|
| /revive | /revive [id] | Revive player |
| /heal | /heal [id] | Full heal player |
| /sethealth | /sethealth [id] [amount] | Set health |
| /setarmor | /setarmor [id] [amount] | Set armor |

## Admin Menu

Access the full admin menu:
- Command: `/admin` or `/adminmenu`
- Opens qb-adminmenu interface
- All commands available through UI

## Logging

All admin actions are logged:
- Discord webhooks
- Database records
- Include your reasoning

## Best Practices

1. **Document everything** - Use proper reasons
2. **Be fair** - Apply rules consistently
3. **Verify first** - Check before taking action
4. **Escalate when needed** - Ask senior staff
5. **Stay calm** - Professional at all times
6. **Announce actions** - Inform affected players
