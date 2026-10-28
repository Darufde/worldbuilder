# Worldbuilder

A browser-based encyclopedia for building your own fictional world. No install or server needed.

## Getting started

Open `builder/index.html` in your browser (double-click it). Click **Load a sample world** to explore, or start writing your own.

## What you can record

| Volume | Examples |
| --- | --- |
| ⚔ History | wars, coronations, disasters (with start/end dates) |
| 📜 Lore | myths, legends, prophecies, songs |
| 👤 People | rulers, heroes, villains (born/died, title, species) |
| 🛡 Organizations | kingdoms, noble houses, guilds, orders, cults |
| 🏰 Places | continents, cities, ruins. Upload a map to pin it |
| 🐉 Species & Creatures | sapient races, beasts, monsters |
| ✨ Magic & Technology | magic systems, spells, inventions |
| 🗡 Items & Artifacts | relics, weapons, books |
| ☀ Religions & Gods | deities, pantheons, faiths |
| 🎭 Cultures | languages, customs, values |
| ◆ Your own types | add Ships, Planets, Spells… with their own fields on the **⚙ World** page |

Every entry has a summary, an article (supports `# heading`, `**bold**`, `*italic*`, `- lists`, `> quotes`), an image, tags, relationships to other entries, and 🔒 secret notes. You can also add extra fields to any built-in type.

## Views

- **Codex**: the front page with "On this day", a 🎲 random-entry button, the volumes, recent entries, and search, tags and ★ pinned entries in the sidebar.
- **Timeline**: every dated entry in order, grouped into the eras you define.
- **Calendar**: your world's own months, weekdays and holidays, with events marked on their days. "On this day" maps today's real date onto your calendar.
- **Web**: an interactive graph of relationships and article links.
- **Maps**: any Place with an image becomes a zoomable map. Drop pins that link to entries, and drag them to move them.
- **Family**: lineage charts built from *Parent of*, *Child of*, *Spouse of* and *Sibling of* relationships.
- **Politics**: a grid of who is at war, allied, rivals, trading or a vassal of whom. Click a square to change it.
- **More ▾**:
  - **📖 Read as a book**: a cover, contents, one volume per chapter and a chronology. Print it or save it as a PDF.
  - **📝 Still to write**: unwritten links, empty articles, missing summaries and pictures, and unconnected entries.
  - **🗑 Recently deleted**: restore deleted entries along with their connections. Deleting also offers an immediate Undo.
  - **📚 Worlds library**: keep several worlds in one browser; open, duplicate, export or delete them.

### Links

Type `[[` in any article to get a list of entries to link to. Write `[[Name|other words]]` to show different text.

- Links to entries that don't exist yet show in orange. Click one to create that entry with its title already filled in.
- Each entry has a **Mentioned in** list of the articles that link to it.
- Renaming an entry updates every link to it.
- Hovering over a link shows a preview card of the entry.

### History

Each save keeps the previous version of the entry (up to 25). The 🕓 button on an entry lists them, and any version can be restored.

### Light and dark

The ☾ / ☀ button in the header switches between the parchment and dark-tome themes. Your choice is remembered, and it works in exported encyclopedias too.

## Saving and exporting

Your worlds autosave in the browser. To keep a real copy, use **Export**:

- **Save both to builder folder…**: in Chrome or Edge, pick `builder/exports` once and it writes both files there directly.
- **Download world file (.json)**: the editable save file, including history and the bin. Load it back with **Import world file…**, which adds it to your library.
- **Download encyclopedia (.html)**: a single standalone, read-only page of your world that you can share. It includes the maps, trees, politics, calendar and book. You choose whether to include secret notes; edit history and deleted entries are always left out.

In other browsers the files download normally. Move them into `builder/exports/`.
