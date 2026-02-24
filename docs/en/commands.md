---
title: Commands
icon: material/code-tags
---

Records module has various commands you can utilize.

| Command | Example | Description |
|:--------|:--------|:------------|
| `!help` | `!help` | Show all available commands. |
| `!map @code` | `!map @7975329` | Load a map. |
| `!map @code r` | `!map @7975329 r` | Load a map in reversed/mirrored orientation. |
| `!map #perm` | `!map #3` | Load a random map from a [perm category](../perm-codes.md). |
| `!map #perm r` | `!map #3 r` | Load a random map from a [perm category](../perm-codes.md) in reversed/mirrored orientation. |
| `!restart` | `!restart` | Reload or reopen the current map while keeping map orientation. |
| `!restart <reversed>` | `!restart no` | Reload or reopen the current map in normal orientation. |
| `!restart <reversed>` | `!restart yes` | Reload or reopen the current map in reversed/mirrored orientation. |
| `!bindmort <key>` | `!bindmort g` | Bind keyboard key to `/mort` action. |
| `!history` | `!history` | View previously loaded maps in current session. |
| `!pw <password>` | `!pw verysecretpw` | Set room password. |
| `!lock <mice>` | `!lock 5` | Set mice limit in the room. This will not kick existing mice in the room. |
| `!submit` | `!submit` | Generate submission hash message. |
| `!time <seconds>` | `!time 360` | Change remaining time in the room. While the module never skips a map after timeout, some game mechanics may require remaining time to function. |
| `!roommod <name>` | `!roommod Friend#1234` | Make someone a room mod allowing them to change map or use other room management commands. |
| `!spectator` | `!spectator` | Toggles spectator mode. |
| `!ban <name>` | `!ban Ignored#1234` | Kills and prevents a player from respawning. |
| `!unban <name>` | `!unban Ignored#1234` | Allows previously banned player to respawn again. |
