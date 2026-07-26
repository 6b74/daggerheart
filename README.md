# Daggerheart Character Sheet

A static, single-page interactive character sheet for [Daggerheart](https://www.daggerheart.com) play sessions. Runs entirely in the browser with no server, no build step, and no dependencies. Designed for iPads and laptops at the table.

## How to Use

**Three ways to load a character:**

1. **Upload JSON** - load a `.json` character file
2. **Paste JSON** - paste raw JSON into a text box
3. **Paste Summary** - paste any freeform character notes (from a builder, markdown sheet, handwritten notes, etc.) and the parser extracts what it can, then lets you review and fill gaps

## Interactive Trackers

All tracker state saves to your browser's localStorage and persists between sessions:

- Hit Points, Stress, Armor Slots (tap to mark/unmark)
- Hope (diamond display with +/- buttons)
- Rally Die and per-rest abilities (Ready/Used toggles)
- Tide Tokens, Gold (Handfuls/Bags/Chest)
- Session Notes (freeform text)
- Quick actions: New Session, Short Rest, Long Rest (auto-reset relevant trackers)

## Other Features

- **Export JSON** - download your character as a `.json` file to share or back up
- **Level Up** - increments level, auto-bumps proficiency at 2/5/8, shows tier advancement checklist
- **Multi-class support** - select "Multi" in the class dropdown during character setup
- **Auto-reload** - remembers last loaded character on refresh

## Templates

The `templates/` folder has blank JSON templates for all 9 classes, pre-filled with class-specific starting stats (domains, evasion, HP, class features, hope feature). There's also a filled example (`trill-example.json`).

- `bard.json`
- `druid.json`
- `guardian.json`
- `ranger.json`
- `rogue.json`
- `seraph.json`
- `sorcerer.json`
- `warrior.json`
- `wizard.json`

## Hosting

Drop the repo on GitHub Pages (Settings > Pages > Deploy from branch > `main`, root `/`). No build step needed, it's a single `index.html`.

## Attribution

This project is unofficial fan content. It includes references to the Daggerheart System Reference Document 1.0, (c) Critical Role, LLC., under the terms of the Darrington Press Community Gaming License (DPCGL). More information at [daggerheart.com](https://www.daggerheart.com).
