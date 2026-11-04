# AGENTS.md

This folder is an Obsidian vault: plain Markdown notes that a person reads and writes in Obsidian. You are helping that person keep it. Read this before you change anything.

## Layout

- `Daily/YYYY-MM-DD.md`: one note per day, made from `Templates/Daily note.md`. The file name is the date.
- `Inbox/`: loose notes that haven’t been sorted yet. New notes from Obsidian land here.
- `Templates/`: templates Obsidian fills in. `{{date}}`, `{{time}}` and `{{title}}` are placeholders; leave them as they are.
- `Daily notes.base`: an Obsidian Bases view (YAML). Edit it only when asked.
- `.obsidian/`: Obsidian’s settings. Don’t touch it.

## Conventions

- Plain Markdown. Properties go in YAML frontmatter at the top of a note.
- Link notes with wikilinks: `[[2026-11-03]]`, `[[Note name]]`. Keep links working when you rename or move a note.
- Tasks are `- [ ]` and `- [x]`. Never mark a task done unless the person says it is.
- Dates are `YYYY-MM-DD`.
- A daily note’s sections, in order: Top priorities, Inbox, Notes log, Open loops, End-of-day review (Recap, Carry forward, Tomorrow).

## Rules

- These are someone’s own notes. Keep their words; don’t rewrite them unless asked.
- Ask before you delete a note, move more than a few notes, or change a template.
- To create today’s note, copy `Templates/Daily note.md` to `Daily/YYYY-MM-DD.md` and fill in the date placeholders.
- When sorting the inbox, move each item into the note it belongs to and link back to where it came from. Leave anything unclear in `Inbox/` and say so.
- Say what you changed, file by file, when you finish.

## Common requests

- "Sort my inbox": move dated items into that day’s note, everything else into a new or existing note; leave what’s unclear.
- "Review today": fill in Recap from the Notes log, list unfinished tasks under Carry forward, suggest one line for Tomorrow.
- "Carry forward": copy yesterday’s unfinished tasks into today’s Top priorities or Open loops.
- "What did I do this week?": read the last seven daily notes and answer with links to each day.
