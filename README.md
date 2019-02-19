# HeadCount
HeadCount is a configurable World of Warcraft add-on that automatically tracks raid attendance, loot, and boss kills.

HeadCount answers the following questions:

- How long is a player active in a raid?
- How long is a player on standby for a raid?
- How long is a player offline during a given raid?
- What loot dropped during a raid and who received it?
- What boss kills occurred during a given raid and who was there for the kill?

### This is a backwards ported release of version r118 to TBC 2.4.3

_Credit goes to Seppyk who was the original author of this addon and maintained it up to 3.3.5_

## Features
### Raids
- Raid creation: Automatically creates a new raid as you join or start a raid.
- Raid finalization: Automatically ends an existing raid as you leave a raid.
- Raid management: The user can end raids, remove raids, or remove all raids on demand.
- Raid zone tracking: Zone name are automatically added to raids as you zone into a raid instance for the first time.
### Player attendance
- Player tracking: Players are tracked based on their timed participation in the raid. Players can be tracked based on configurable raid groups for raid list activity (active raiding players) and wait list players (queue/standby players).
- Player removal: The user can remove tracked information for specific players on demand.
- Player history: View specific player history for a raid to see how and when a player moved from activity to standby to offline and back during a raid.
- No list tracking: Players can be tracked as non-raid list and non-standby players as needed. Players that go offline are automatically taken out of the raid and wait list groups for tracking purposes.
- Integrated wait list: Receive whispers from members outside of the raid group in order to track them.
### Boss kills
- Boss kill tracking: Tracks the world bosses killed during the course of a raid and the raid list members present for the kill.
- Boss kill removal: The user can remove tracked boss kills on demand.
- Manual boss kill: The user can add a boss kill to the current raid at the current time with the current roster via /hc boss add [bossname]
### Loot
- Loot tracking: Tracks loot received during a raid based on configurable item level quality (default: Epic item level or higher)
- Loot removal: The user can remove specific pieces of loot on demand.
- Loot exclusion: The user can manage loot exclusion which will prevent certain pieces of loot from being tracked during a raid. (e.g. - Emblem of Valor)
Export
- Export: Users can export current raid attendance and received loot information to one of a number of formats (CSV, XML, Text, EQdkp XML string, phpBB forum post, phpBB with ItemStats forum post).
### Reporting
- Boss kill broadcast: The user can optionally broadcast when the raid kills a boss to a configurable chat channel.
- Loot broadcast: The user can optionally broadcast when a player receives a valid piece of loot to a configurable chat channel.
Performance
- Fault tolerance: If the mod owner quits WoW, restarts WoW, or reloads their UI during a raid and returns to the game, HeadCount will attempt to gracefully recover from the outage to continue tracking the active raid.
- Attendance delay: Configure how often HeadCount should manage attendance updates to increase or decrease performance and/or accuracy.
