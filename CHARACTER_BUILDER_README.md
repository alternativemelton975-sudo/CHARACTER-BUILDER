# Character Builder

An RPG character creation and management system with battle simulations and team management.

## Features

- **Create Characters** - Build RPG characters with random stats
- **Character Profiles** - View detailed character information
- **Battle Simulator** - Simulate battles between characters with experience gain
- **Team Management** - Create and manage teams of characters
- **Character Persistence** - Save/load characters from JSON files
- **Experience System** - Level up characters through battles

## Requirements

- Python 3.11+
- No external dependencies (uses only standard library)

## Installation

```bash
git clone https://github.com/yourusername/character-builder.git
cd character-builder
python KingMyer.py
```

## Usage

```bash
python KingMyer.py
```

### Menu Options

1. **Create New Character** - Generate a new character with stats
2. **View Character Profile** - Display detailed character information
3. **Battle Simulator** - Battle two characters
4. **Manage Team** - Create and view character teams

## Character Stats

- Strength (5-20)
- Intelligence (5-20)
- Agility (5-20)
- Endurance (5-20)

## Example

```
=== KINGMYER CHARACTER BUILDER ===

1. Create new character
2. View character profile
3. Battle simulator
4. Manage team

Choose option (1-4): 2
Character name: Aragorn
Character power: sword

==================================================
⚔️  ARAGORN
==================================================
Level: 1 | Experience: 0
Primary Power: sword

STATS:
  Strength: 18
  Intelligence: 12
  Agility: 15
  Endurance: 16

Total Power: 61
==================================================
```

## Docker

```bash
docker build -t character-builder .
docker run -it character-builder:latest
```

## License

MIT
