# DeadMansCove
Pirate Game Planning

# Pirate Island Game State Components

## Player State
- **Identity**: Role as a Crewmate or Pirate.
- **Location**: Position on the island or ship.
- **Status**: Alive, dead, or marooned (after walking the plank).
- **Task Progress**: List of island and ship tasks and their status for Crewmates.
- **Cooldowns**: For Pirates, cooldown timers for actions like attacking or causing mischief.
- **Visibility**: Affected by environmental factors like nighttime, fog, or ship's dark corners.

## Task State
- **Type of Tasks**: Various tasks categorized as simple, complex, or communal.
- **Location**: Specific locations on the island or different parts of the ship.
- **Completion Status**: Pending, in progress, or completed.
- **Assignments**: Which players have been assigned which tasks.

## Map State
- **Layout**: Includes both the island's topography and the ship's structure with unique areas.
- **Sabotage States**: Status of different elements on the ship and island that can be tampered with.
- **Interactive Elements**: Things like hidden treasures, ship controls, lookout points, and booby traps.

## Council State
- **Availability**: When players can gather for a council (either finding a sabotaged element or using a special conch shell).
- **Discussion Time**: Time for players to discuss suspicions.
- **Voting Time**: The duration for casting votes.
- **Vote Results**: Who was voted to walk the plank.

## Game Progress State
- **Number of Pirates Remaining**: Count of Pirates still causing mischief.
- **Number of Crewmates Remaining**: Count of active Crewmates.
- **Task Completion Meter**: Overall progress of tasks by the Crewmates.
- **Win Conditions**: Conditions for a win by either Crewmates or Pirates.

## Timer and Cooldowns
- **Attack Cooldown**: Time Pirates must wait between attacks.
- **Council Cooldown**: Interval before another council can be convened.
- **Mischief Cooldown**: Waiting period before causing another disruption.

## Event Log
- **Actions Taken**: Records of key actions by players (completing tasks, attacks, causing mischief).
- **Councils and Votes**: Details and outcomes of discussions and votes.

## Network State (for Online Play)
- **Player Connections**: Monitoring of player connectivity.
- **Data Sync**: Ensuring game state synchronization across all players.
