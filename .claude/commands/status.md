---
description: Health-check local services and report the status of every project.
---

# /status: what's actually running

Read only. Report; don't start or stop anything unless the user asks.

1. Read `services.json` at the vault root. For each service with a `health` URL:
   - only check `http://127.0.0.1` or `http://localhost` URLs; skip any other host and say so;
   - request it with a short timeout (`curl -s -o /dev/null -w "%{http_code}" --max-time 3 <url>`
     in bash, or `Invoke-WebRequest -TimeoutSec 3` in PowerShell);
   - mark it UP for any HTTP response under 500, DOWN otherwise.
2. Read the Layer-1 projects table in `CLAUDE.md` and the **Status** line of each project's
   Layer-2 `CLAUDE.md`.

Print two tables and one line:

```
SERVICES
service · port · tier · UP/DOWN · start command

PROJECTS
project · status · next action · last updated

FIX FIRST: <the always-on service that is DOWN, with its start command — or "nothing">
```

No prose beyond that. If `services.json` is missing or still holds only the examples, say so
and point to it.
