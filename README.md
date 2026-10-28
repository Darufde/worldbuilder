# Worldbuilder

A browser-based encyclopedia for building your own fictional world. No install or server needed.

## Getting started

Open `builder/index.html` in your browser (double-click it). Click **Load a sample world** to explore, or start writing your own.

## What you can record

| Volume | Examples |
| --- | --- |
| ⚔ History | wars, coronations, disasters (with start/end years) |
| 📜 Lore | myths, legends, prophecies, songs |
| 👤 People | rulers, heroes, villains (born/died, title, species) |
| 🛡 Organizations | kingdoms, guilds, orders, cults |
| 🏰 Places | continents, cities, ruins. Upload maps as images |
| 🐉 Species & Creatures | sapient races, beasts, monsters |
| ✨ Magic & Technology | magic systems, spells, inventions |
| 🗡 Items & Artifacts | relics, weapons, books |
| ☀ Religions & Gods | deities, pantheons, faiths |
| 🎭 Cultures | languages, customs, values |

Every entry has a summary, an article (supports `# heading`, `**bold**`, `*italic*`, `- lists`, `> quotes`), an image, tags, relationships to other entries, and 🔒 secret notes.

### Links

Type `[[` in any article to get a list of entries to link to. Write `[[Name|other words]]` to show different text.

- Links to entries that don't exist yet show in orange. Click one to create that entry with its title already filled in.
- Each entry has a **Mentioned in** list of the articles that link to it.
- Renaming an entry updates every link to it.
- Links also show as dashed lines in the **Web**.

### Light and dark

The ☾ / ☀ button in the header switches between the parchment and dark-tome themes. Your choice is remembered, and it works in exported encyclopedias too.

## Views

- **Codex**: the front page, the volumes, and search and tags in the sidebar.
- **Timeline**: every dated entry in order, grouped into the eras you define under **⚙ World**.
- **Web**: an interactive graph of the relationships between entries.

## Saving and exporting

Your world autosaves in the browser. To keep a real copy, use **Export**:

- **Save both to builder folder…**: in Chrome or Edge, pick `builder/exports` once and it writes both files there directly.
- **Download world file (.json)**: the editable save file. Load it back with **Import world file…**.
- **Download encyclopedia (.html)**: a single standalone, read-only page of your world that you can share. You choose whether to include secret notes.

In other browsers the files download normally. Move them into `builder/exports/`.
