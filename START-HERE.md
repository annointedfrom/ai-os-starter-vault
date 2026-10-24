# START HERE

The front door to this vault, for you and for Claude.

## Setup (10 minutes)

1. Open this folder as a vault in [Obsidian](https://obsidian.md).
2. Open a terminal in this folder and run `claude` ([Claude Code](https://docs.claude.com/en/docs/claude-code/overview)).
3. Fill in the placeholders in [[CLAUDE]] (the Layer-1 brain): who you are, how you work, your projects.
4. Copy `Projects/_example-project/` for your first real project and fill in its `CLAUDE.md`.
5. Run `/start`.

## The map

```
CLAUDE.md            Layer 1: identity, projects, rules  ← read first
START-HERE.md        this file
LOOSE-ENDS.md        parked or half-finished work
services.json        local services /status health-checks
Projects/            active work, one Layer-2 CLAUDE.md each
Areas/               ongoing responsibilities
Resources/           reference material
Sandbox/             code workshop
Daily/               YYYY-MM-DD.md notes
Ideas/               raw brainstorming (never auto-cleaned)
Archive/             finished work
_templates/          note templates
.claude/commands/    /start and /status
```

## The two layers

- **Layer 1** (`CLAUDE.md` at the root) is short and always loaded: who you are, what's active, the rules.
- **Layer 2** (`<folder>/CLAUDE.md`) holds the detail for one folder or project. Claude reads it only when work touches that folder, so context stays small and focused.

## Daily loop

1. `/start` in the morning: state + the one thing.
2. Work. Ask Claude to log decisions into the project's Layer-2 file.
3. Append what you did to `Daily/YYYY-MM-DD.md` (template in `_templates/daily-note.md`).
4. Park anything unfinished in [[LOOSE-ENDS]] so tomorrow's `/start` sees it.
