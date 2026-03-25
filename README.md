# 30-Day Challenge Tracker

A beautiful, fully self-contained habit tracker for 30-day challenges. No app install, no account, no server — just open the link and start.

![30-Day Challenge](https://img.shields.io/badge/habit--tracker-30--day-4a9d6f?style=flat-square) ![No dependencies](https://img.shields.io/badge/dependencies-none-blue?style=flat-square) ![Offline ready](https://img.shields.io/badge/offline-ready-brightgreen?style=flat-square)

---

## Live Demo

👉 **[Open the tracker](https://vsurya08.github.io/30day-challenge)**

---

## What it does

You define your challenge. The tracker keeps you honest.

On first open, a short setup screen asks for:
- Your name
- A challenge title (e.g. "Morning Routine", "Health Reset", "Focus Month")
- A start date
- 2–6 habits you want to build

After that, you get a full 30-day tracking dashboard with three views:

| View | What you see |
|---|---|
| **Daily** | Today's habits as large tap-to-check rows — best for daily use |
| **Weekly** | All 5 weeks laid out as a grid with checkboxes per day |
| **Monthly** | Full 30-day heatmap with coloured pips showing habit completion |

---

## Features

- **Per-habit completion %** — each habit tile shows how consistent you've been across all 30 days
- **Streak counter** — consecutive days where at least one habit was completed
- **Perfect days** — days where every single habit was checked off (highlighted in green)
- **Drag to reorder** — rearrange habit tiles in any order by dragging
- **Add / edit / delete habits** — fully customisable at any time via the settings panel
- **Daily motivational quote** — a fresh AI-generated quote each day, tailored to your specific habits
- **Offline-ready** — works without an internet connection after the first load (quote generation requires connection)

---

## How data is stored

All your entries are saved to your browser's **localStorage** — they stay on your device, in your browser. Nothing is sent to a server. Your data is private by default.

This also means:
- Progress doesn't sync across devices or browsers
- Clearing browser data will erase progress
- Each person who opens the link gets their own independent tracker

If you want to back up your data, use the export option in the settings panel (if enabled).

---

## How to use

1. Open the link above
2. Fill in your name, challenge title, start date, and habits on the setup screen
3. Click **Start my challenge**
4. Each day, open the tracker and check off your habits in the Daily view
5. Use Weekly or Monthly views to review your progress

---

## Customising your habits

Open the **Customize habits** panel at any time to:
- Rename any habit or its short label
- Add a new habit (up to 6 total)
- Delete a habit you no longer want to track
- Drag tiles on the main screen to reorder them

---

## Deploying your own copy

This is a single HTML file with no external dependencies (except Google Fonts and the AI quote feature).

To host your own copy:

```bash
# Clone the repo
git clone https://github.com/yourusername/30day-challenge.git

# The only file you need is index.html
# Open it directly in a browser, or deploy to any static host
```

**Free hosting options:**
- [GitHub Pages](https://pages.github.com) — already set up if you're reading this
- [Netlify Drop](https://app.netlify.com/drop) — drag and drop the file for an instant URL
- [Vercel](https://vercel.com) — one-command deploy

---

## Tech stack

| Layer | What's used |
|---|---|
| UI | Vanilla HTML, CSS, JavaScript — zero frameworks |
| Fonts | DM Serif Display + DM Sans via Google Fonts |
| Storage | Browser localStorage |
| AI quotes | Anthropic Claude API (claude-sonnet-4) |

---

## Credits

Built as a personal productivity tool and shared as an open template. Feel free to fork, modify, and share.

---

## Licence

MIT — use it, share it, build on it.
