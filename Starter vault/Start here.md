# Start here

A small vault that does one thing well: a daily note, an inbox and instructions an AI agent can follow.

## Use it

1. Click **Open today’s daily note** in the left ribbon. It opens on its own each time you start Obsidian, too.
2. Put anything you don’t want to lose in `Inbox`. New notes land there.
3. At the end of the day, fill in the review at the bottom of today’s note.

[[Daily notes.base|Daily notes]] lists every day you’ve written, newest first.

## Work on it with AI

`AGENTS.md` and `CLAUDE.md` tell Claude Code, Codex and other coding agents how this vault works. Open a terminal in this folder and run `claude` or `codex`, then ask, for example:

> Sort my inbox. Move anything with a date into that day’s note. Ask before you delete anything.

The agent reads and writes ordinary Markdown files. Whatever it reads goes to the provider behind the agent you use.

To chat with Claude Code or Codex inside Obsidian, install the free [SystemSculpt](https://obsidian.md/plugins?id=systemsculpt-ai) plugin. It’s optional; nothing here needs it.

## What’s inside

- `Daily/`: one note per day, named `YYYY-MM-DD`.
- `Inbox/`: loose notes, waiting to be sorted.
- `Templates/Daily note.md`: the template every daily note starts from. Change it freely.
- `Daily notes.base`: a table of your daily notes.
- `AGENTS.md`, `CLAUDE.md`: house rules for AI agents.

Everything uses Obsidian’s core plugins: Daily notes, Templates and Bases. No community plugins.

Made by [SystemSculpt](https://systemsculpt.com). CC BY 4.0: use, change and share it, with credit to SystemSculpt.

Want more? [[Next step]]
