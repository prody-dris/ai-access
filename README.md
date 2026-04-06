# AI Access Directory — Dhwani RIS

A simple, public page showing who has access to which AI tools (Cursor, Claude) at Dhwani RIS.

**Live site:** https://prody-dris.github.io/ai-access/

## What this is

A single-page directory that answers:
- Which AI tool accounts exist
- Who manages each account
- Who is currently sharing access

## How to update

Edit `data.json` in this repo. The page reads from it automatically on every load.

- **Add/remove people:** Update the `members` arrays
- **Add a new account:** Add a new entry to the relevant tool section
- **Change an owner/leader:** Update the `owner` or `leader` field

After editing, commit and push. GitHub Pages rebuilds within a few minutes.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The page itself |
| `data.json` | All account data — the single source of truth |

## Managed by

Ravi & Ankit. Questions? Reach out on Teams.

---
*Dhwani Rural Information Systems | Internal use*
