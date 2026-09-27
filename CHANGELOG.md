# Changelog

All notable changes to Threads are listed here, newest first. Versions follow [semantic versioning](https://semver.org): a new major number for changes that could break saved timelines or exported files, a new minor number for new features, and a new patch number for fixes.

## [Unreleased]

Nothing yet.

## [1.0.1] - 2026-09-26

### Fixed

- On self-hosted pages, Export now saves a real `.json` file, or `.html` for a blank copy of the app, instead of showing the text to copy. The text is still shown if a browser can't save files.

## [1.0.0] - 2026-09-26

The first public release.

### Timeline

- Lanes for parties, characters and world events, side by side day by day, with connections between lanes and shaded spans.
- A day panel that folds each event to its lane, title, place and summary, with beats, quotes and notes a click away and a "Show all details" switch.
- Follow a name, place or word to light up every day it appears, including matches hidden inside an event's details.
- Event labels: confirmed, partly known, placeholder and upcoming.

### Who's where

- Lists who is with each party on every day, marked as joining, rejoining or departing, with the reason for a departure.
- Same-day moves between parties, shown on both lanes.
- Edit people in place from the day panel: move, depart, stay after all, or change a stint's dates.
- Add several people to a party in a row, including someone who has been there all along.
- Turn it on or off for each lane.

### Time running differently

- Spans where time runs faster, with a spot for an event on each local day.
- Spans where time runs slower, where one local day covers several days here.
- Every event in such a span shows its local day.
- Threads asks before combining events when a span is made slower.

### Editing

- Select first, then act: clicking an empty spot selects it, and nothing is created until you choose to add an event.
- Insert or remove a day for one lane only, or for every lane.
- Tabbed Timeline settings: Timeline, Lanes, Spans and Characters.
- Private notes that stay in your copy unless you choose to export them.
- Undo for every change.

### Sharing

- Each player's copy is saved in their own browser.
- Export and import timeline files.
- Merge a player's file: review every new and changed entry and pick what to bring in, with nothing of yours removed.
- Publish to a claude.ai page, or host the single HTML file anywhere.
- A notice when a newer version is published, with the choice to load it, keep it alongside your copy, or keep yours.
- Export a blank copy of Threads for another group.

### Help

- A welcome screen for first-time visitors.
- Built-in help, and a link to the full guide.
- The version number and credit in the footer.

[Unreleased]: https://github.com/XoYdiuM/dndthreads/compare/v1.0.1...HEAD
[1.0.1]: https://github.com/XoYdiuM/dndthreads/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/XoYdiuM/dndthreads/releases/tag/v1.0.0
