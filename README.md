# wordmill-data

Machine-readable JSON data extracted from Word Mill Games publications for use in solo RPG tools and engines.

## Contents

- `mythic_gme_2e.json` — Mythic Game Master Emulator Second Edition. Fate chart, fate check modifiers, random event focus table, meaning tables (actions, descriptions, 45 themed element tables), scene adjustment table, NPC behavior table, chaos factor variants.
- `adventure_crafter.json` — The Adventure Crafter. 186 plot points across 5 themes, meta plot points, character special traits, character identity table, character descriptors, theme translation table.

## Data Validation

All tables verified complete:
- Fate chart: 9 odds × 9 chaos factor = 81 cells, all present
- Event focus table: 12 entries covering d100 range 1-100
- Meaning tables (actions): 100 verbs + 100 subjects
- Meaning tables (descriptions): 100 adverbs + 100 adjectives
- Element tables: 45 tables, each 100 entries
- Plot points: all 5 themes cover d100 range 1-100 with no gaps

## Licensing

This data is derived from works by Tana Pigeon, published by Word Mill Games, under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license.

You may share and adapt this data for non-commercial purposes with appropriate attribution.

### Attribution

"This work is based on Mythic Game Master Emulator Second Edition by Tana Pigeon, published by Word Mill Games, and licensed for our use under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license. Find out more at www.wordmillgames.com."

"This work is based on The Adventure Crafter by Tana Pigeon, published by Word Mill Games, and licensed for our use under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license. Find out more at www.wordmillgames.com."

## Source

Extracted using PyMuPDF from officially purchased PDFs. The extraction tool is not included in this repository to avoid facilitating unauthorized reproduction. Purchase the original works at [DriveThruRPG](https://www.drivethrurpg.com/browse/pub/480/Word-Mill-Games) or [itch.io](https://wordmillgames.itch.io/).
