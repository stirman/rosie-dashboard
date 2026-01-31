# Rosie Dashboard

Daily infographic dashboard showing Rosie's status, weather, activities, and ideas.

## Quick Reference
| Field | Value |
|-------|-------|
| **Location** | `/Users/rosie/clawd/stirman/rosie-dashboard` |
| **GitHub** | stirman/rosie-dashboard |
| **Type** | Static Web (HTML/CSS/JS) |
| **Live URL** | https://stirman.net/rosie-dashboard/ |
| **Hosting** | GitHub Pages |
| **Last Update** | Check git log |

## Deploy Process
```bash
cd ~/clawd/stirman/rosie-dashboard

# 1. Edit data.json with new content
# 2. Commit and push
git add -A && git commit -m "Update dashboard" && git push

# GitHub Pages auto-deploys on push
```

## Key Files
- `index.html` — Main dashboard page
- `data.json` — Dynamic content (weather, status, ideas)
- `style.css` — Styling

## Architecture Notes
- Pure static site, no build step
- JavaScript fetches `data.json` for dynamic content
- Hosted via GitHub Pages

## Recent Changes
- **2026-01-26**: Initial setup

## Known Issues
- None

## TODO / Next Steps
- [ ] Auto-update via heartbeat/cron
