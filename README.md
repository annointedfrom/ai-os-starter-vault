# AI OS Starter Vault

A free Obsidian vault that turns [Claude Code](https://docs.claude.com/en/docs/claude-code/overview)
into a co-worker who knows your projects. Open the folder, fill in one file, run `/start`.

## What you get

- **A two-layer brain.** A short root `CLAUDE.md` (who you are, what's active, the rules) plus a
  Layer-2 `CLAUDE.md` in every folder and project, loaded only when work touches it. Claude starts
  each session knowing your context without reading your whole vault.
- **`/start`**: a morning boot that reads your projects, loose ends and today's note, then names
  **one** thing to do.
- **`/status`**: health-checks your local services and lists every project's status.
- **A folder system that stays tidy**: Projects, Areas, Resources, Sandbox, Daily, Ideas, Archive,
  each with rules Claude follows (for example, it never reorganizes `Ideas/`).
- **Templates** for a project and a daily note.

## Quick start

1. Download or clone this repository:

   ```bash
   git clone https://github.com/annointedfrom/ai-os-starter-vault.git my-vault
   ```

2. Open `my-vault` as a vault in [Obsidian](https://obsidian.md).
3. In a terminal inside `my-vault`, run `claude`.
4. Fill in the `<…>` placeholders in `CLAUDE.md`, or ask Claude: *"interview me and fill in CLAUDE.md"*.
5. Copy `Projects/_example-project/` for your first project.
6. Run `/start`.

Read [START-HERE.md](START-HERE.md) for the map and the daily loop.

## Requirements

- Obsidian (free)
- Claude Code with a Claude subscription or API key
- Optional: git, and any local services you want `/status` to watch (listed in `services.json`)

## Privacy

Everything stays in this folder on your machine. The kit contains no telemetry and makes no
network calls except the `localhost` health checks you list in `services.json`. Keep secrets
out of the vault; `.gitignore` already excludes common secret files.

## Want more?

This free kit is the foundation of a larger system with more commands (`/ship`, `/advisor`,
`/loose-ends`), specialist agents, a local-AI stack and a memory layer.
<!-- Add your store link here when the paid kit is live. -->

## Credits

The layered `CLAUDE.md` approach follows the "AI second brain" pattern popularized in the
Obsidian + Claude Code community, and the folder system borrows from PARA.

## License

[MIT](LICENSE)
