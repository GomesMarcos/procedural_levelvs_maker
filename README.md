# procedural_levelvs_maker
This is a tool for generating Tabletop RPG dungeons.

## Main Goals
- Generate the dungeon. Parameeters:
  -- width (int)
  -- height(int)
  -- has_entry (bool)
  -- quantity__entries (int) -> if has_entry, min 1, max (width * height) * 0.9

- Customize dungeon floor and wall cells. Valid formats to import (max file size: 1MB):
  --jpg
  --jpeg
  --png
  --svg

- Export dungeon. formats:
  --jpg
  --jpeg
  --png
  --svg
