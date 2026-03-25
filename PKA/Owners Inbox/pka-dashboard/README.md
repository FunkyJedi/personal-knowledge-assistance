# PKA Command Center

A read-only dashboard for the PKA AI Team's SQLite database (`pka.db`). Single-page application — no build step, no dependencies.

## How to Open

Double-click `index.html` or run:

```bash
open "/Users/Mike_L/_Code/PKA/Owners Inbox/pka-dashboard/index.html"
```

Works in Safari, Chrome, Firefox, or any modern browser.

## What You'll See

- **Dashboard** — Overview stats (team members, open tasks, projects, pending actions, inbox, knowledge base), recent activity timeline, team roster, and pending action items
- **Tasks** — Table view of all tasks with status, priority, assignee, and domain
- **Projects** — Table view with linked tasks and meetings in detail view
- **Team** — Card grid of all members; click for profile, assigned tasks, action items, and activity history
- **Knowledge** — Entries with tags, types, cross-links, and full content in detail view
- **Meetings** — Meeting records with notes and linked action items
- **Inbox** — Team and owner inbox items with processing status
- **Hiring** — Pipeline entries from research through approval
- **Activity** — Full chronological log of all team actions

## Features

- Dark/light mode toggle (persists via localStorage, defaults to system preference)
- Global search filters across all fields in the current view
- Click any row to open a detail slide-in panel with full data and relationships
- Keyboard navigable (Tab, Enter, Escape to close panels)
- Color-coded status badges and priority indicators
- Responsive layout

## Data

Current database snapshot is embedded as JavaScript constants at the top of `index.html`. To update with fresh data, re-query `pka.db` and replace the `DB` object.

## Built By

Kael — Senior UI/UX Application Developer, PKA AI Team
