# Sandbox — Layer 2

> ⬆ Parent: [[../CLAUDE|Layer 1]]

## Purpose

The workshop. Code is written and run here before it earns a place in `Projects/`.
Notes elsewhere in the vault are for *thinking about* code; this folder is where it lives.

## Promotion path

```
learning/ ──[used twice, or solves a recurring annoyance]──> tools/
tools/    ──[several modules, config, persistence, tests]──> projects/
```

Code that hasn't graduated within about three months gets archived or deleted.

## Rules

1. **Make it its own git repo** (`git init` here). Keep it separate from your notes.
2. **No secrets in code.** Use environment variables or a secrets file that is gitignored.
3. **Tests before "done".** Anything that graduates to `projects/` has a test run that passes.
4. **Date-prefix practice folders** (`learning/2026-10-23-recursion/`) so old exercises are easy to find and obviously frozen.

## Folders

| Folder | For |
|---|---|
| `learning/` | exercises and experiments |
| `tools/` | small utilities you use more than once |
| `projects/` | larger code with its own Layer-2 `CLAUDE.md` |
