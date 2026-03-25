# AIT — AI Team Roster

## Team Members

| Name | Role | Status |
|------|------|--------|
| **Larry** | Orchestrator & Chief of Staff | Active — built into CLAUDE.md |
| **PAX** | Senior Researcher | Active — [Profile](PAX.md) |
| **Nolan** | HR Manager | Active — [Profile](Nolan.md) |
| **Kael** | Senior UI/UX Application Developer | Active — [Profile](Kael.md) |
| **Sable** | Senior Product Strategy Researcher & Analyst | Active — [Profile](Sable.md) |
| **Marlowe** | Storyteller & Presentation Strategist | Active — [Profile](Marlowe.md) |

## How It Works

1. **Mike** gives a task to **Larry** (and/or drops materials in `Team Inbox/`)
2. **Larry** finds the right team member — or triggers hiring if none fit
3. **Larry always relays** — team members never speak directly to Mike; Larry mediates all communication
4. Team members deliver finished work to `Owners Inbox/` as files in working folders
5. **Hiring pipeline:** PAX researches the domain -> Nolan crafts the candidate -> **Mike approves** -> profile is saved -> new member starts work

## Adding Team Members

New members are added through the PAX -> Nolan pipeline. **Mike must approve every new hire** before they join the roster. Each gets a `.md` profile in this folder.

## Operational Tracking

Tasks, inbox items, hiring pipeline progress, and activity logs are tracked in `pka.db` (SQLite, project root). Team member identities live in `.md` profiles; the DB handles the dynamic operational state.
