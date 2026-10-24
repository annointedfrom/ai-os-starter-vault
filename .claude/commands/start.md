---
description: Morning boot. Read the vault's state, report it, and name the ONE thing to do today.
---

# /start: daily driver

This is the first command of the day. Be concise and end with exactly ONE next action.
Read only; don't edit files unless the user asks.

Do this in order:

1. Read `CLAUDE.md` (Layer 1): who the user is, how they work, the active-projects table.
2. Read `START-HERE.md` only if Layer 1 still has unfilled `<…>` placeholders. If it does, say
   so and make "fill in CLAUDE.md" the ONE thing.
3. For each project in the Layer-1 table, read the **Status** and **Next actions** sections of
   its Layer-2 `CLAUDE.md`. Skip `_example-project` unless it is the only project.
4. Read `LOOSE-ENDS.md`.
5. Read today's daily note `Daily/YYYY-MM-DD.md` (use today's local date). If it's missing,
   say so: a missing note is a signal the day hasn't started.
6. If the vault or `Sandbox/` is a git repo, count uncommitted changes with
   `git status --short` (this works the same on Windows, macOS and Linux).

Then report in exactly this shape:

```
STATE
- Projects: <name — status — next action>, one line each
- Loose ends: <count>, oldest: <item> (<date parked>)
- Git: <n uncommitted changes | not a repo>
- Daily note: <present | MISSING — write one line today>

THE ONE THING
<the single highest-leverage action for today>
→ exact file, command or link to start it

THEN (only if energy remains)
<at most 3 parked items, one line each>
```

How to pick THE ONE THING (first rule that applies wins):

1. Something blocking other work (a failing build, a broken service, a deadline within 48 hours).
2. The "Next action" of the project closest to its done-when condition.
3. The oldest item in `LOOSE-ENDS.md`.
4. Otherwise: write today's daily note and pick a project.

Rules:

- No long plans. One thing.
- If the ONE thing needs a command run, give the exact command and folder, then stop.
- Never invent projects or deadlines that aren't written in the vault.
