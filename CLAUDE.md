# CLAUDE.md — Layer 1 (vault root)

> Read first by any Claude session opened in this vault.
> Layer 1 = **who you are + what you're working on + how we work together.**
> Folder details live in Layer-2 `CLAUDE.md` files, one per top-level folder.
>
> New here? Open [[START-HERE]]. Fill in every `<…>` placeholder below; delete what doesn't apply.
>
> ⬇ **Layer-2 indexes:** [[Projects/CLAUDE|Projects]] · [[Areas/CLAUDE|Areas]] · [[Resources/CLAUDE|Resources]] · [[Sandbox/CLAUDE|Sandbox]] · [[Daily/CLAUDE|Daily]] · [[Ideas/CLAUDE|Ideas]]

---

## Who I am

- **Name:** <your name>
- **Role:** <student / founder / engineer / creator …>
- **Platform:** <Windows / macOS / Linux> · shell: <PowerShell / bash / zsh>
- **Strongest languages / tools:** <e.g. Python, TypeScript, Java>
- **What I want from Claude:** <e.g. "a co-founder who ships, not a chatbot that plans">

## How I work

- **Scope:** <go big / small steps>
- **Quality bar:** <production-grade / quick prototypes>
- **Order of work:** plan → test → implement → review → commit.
- **Updates:** short. Reference the agreed plan; don't narrate every step.
- **End every task** with a two-line summary and the next action.

---

## Active projects

| Project | Location | Status | Layer-2 context |
|---|---|---|---|
| <Project name> | `Projects/<folder>/` | <planning / building / live> | [[Projects/<folder>/CLAUDE\|CLAUDE.md]] |
| Example project | `Projects/_example-project/` | template — copy it | [[Projects/_example-project/CLAUDE\|CLAUDE.md]] |

Keep this table current. It is how a fresh session knows what matters.

---

## Vault conventions

| Folder | Role |
|---|---|
| `Projects/` | Active work with a goal and an end. One Layer-2 `CLAUDE.md` per project. |
| `Areas/` | Ongoing responsibilities with no end date (health, school, finances, faith …). |
| `Resources/` | Reference material, tool notes, saved research. |
| `Sandbox/` | Where code is actually written and run before it graduates. |
| `Daily/` | Dated notes `YYYY-MM-DD.md` — append, never overwrite. |
| `Ideas/` | Raw brainstorming. Claude never cleans or reorganizes it unless asked. |
| `Archive/` | Finished or abandoned work. |

**Naming:** kebab-case filenames; daily notes `YYYY-MM-DD.md`; session logs at `<project>/sessions/YYYY-MM-DD.md`.
**Links:** prefer `[[path/to/note|display text]]`.

## How Claude should use this vault

1. **Read this file first.** It sets identity and scope.
2. **When a project is mentioned, load its Layer-2 `CLAUDE.md`** before doing any work there.
3. **Distill, don't dump.** Extract decisions and gotchas into the right Layer-2 file; raw logs go to `Archive/`.
4. **Wikilink instead of copying.** One source of truth per fact.
5. **Don't host code in notes.** Code lives in `Sandbox/` or a project repo; notes are for thinking about it.
6. **Ask before anything outward-facing** — posting, sending, spending, deleting, publishing.

## Hard rules

- No secrets, API keys or passwords in the vault. Keep them in a secrets manager or a file outside the vault.
- `Ideas/` is sacred: never auto-clean it.
- Daily notes are append-only.

## Commands

| Command | What it does |
|---|---|
| `/start` | Morning boot: reads vault state, reports it, and names the ONE thing to do today. |
| `/status` | Health-checks the local services listed in `services.json` and the status of every project. |

---

**Last updated:** <YYYY-MM-DD>
