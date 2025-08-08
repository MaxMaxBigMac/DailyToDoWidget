# The Machine — 3‑Day Cycle (PWA)

A lightweight, offline‑capable web app that rotates a **3‑day A/B/C task cycle** at a custom rollover time (default **3:00 PM**). It shows an interactive checklist for *today’s* day, auto‑resets at rollover, and saves everything locally.

## Features
- Custom **rollover time** (e.g., 3:00 PM so your day matches your sleep schedule)
- **Force next day** (advance the cycle immediately)
- **Manual override** (force Day A/B/C)
- **Editable tasks** for Day A/B/C (one per line; saved locally)
- **Installable** on Android (Add to Home Screen) via PWA, works offline
- No accounts, no servers required once hosted

## Quick Start (GitHub Pages)
1. Create a new repo and drop in these files:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `README.md`
2. Commit and push.
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**; pick `main` and `/ (root)`.
4. Wait a minute. Your site will be live at `https://<username>.github.io/<reponame>/`.
5. Open that URL on Android Chrome → **⋮ → Install app** (or “Add to Home screen”).

## Usage
- Set your **Rollover time** (defaults to 15:00 / 3 PM).
- Optionally set **Start date** to align the cycle with your preferred Day A.
- Use **Force next day** to advance instantly.
- Edit tasks under each Day (A/B/C). One task per line.
- The app saves to localStorage and works offline after first load.

Enjoy!
