# Account Command

Personal account, project, and task management tool. Built for enterprise AI sales workflow.

## Live App

Deployed via Vercel: _coming soon_

## Features

- Account → Project → Task hierarchy
- Smart Today view with overdue, due-today, and P0 surfacing
- Pipeline kanban (Discovery → POC → Proposal → Negotiation → Closed)
- Quick capture with natural language parsing (`Call Saibal tomorrow 4pm P0 @BCG`)
- Inbox for non-account tasks
- Snooze, stale account detection, weighted pipeline forecast
- Keyboard shortcuts (press `?` to see all)
- Local persistence via browser localStorage
- JSON export for backups (press `e`)

## Tech

Single HTML file. No build step, no dependencies, no server. Just open and use.

- Vanilla HTML/CSS/JS
- Browser localStorage for persistence
- Google Fonts (Fraunces + Inter)

## Roadmap

- [ ] Supabase backend for cross-device sync
- [ ] Magic link auth
- [ ] Mobile-friendly snapshot export
