# Comeback OS

Offline-first study and discipline tracker (PWA). No server, no API, no account.

## Deploy on GitHub Pages
1. Create a GitHub repo and upload all files in this folder (index.html, manifest.json, sw.js, icon-192.png, icon-512.png).
2. Repo Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Wait a minute, then open `https://<username>.github.io/<repo>/`.

## Install on Android
Open the link in Chrome > menu (three dots) > "Install app" or "Add to Home screen". It then opens full-screen and works offline.

## Using it
- **Home**: today's progress, streak, pending/missed work, due revisions.
- **Schedule**: tap a slot as done (opens a Study entry) or missed (asks why, can add it to Tasks). "Edit template" adds, edits, deletes slots.
- **Study**: log sessions. Focus time = minutes you log here; breaks never count.
- **More**: Roadmap (Python, 6 statuses), Projects, Data Science course, Trading education, Revision, Analytics, Daily review, Settings.

## Data
Stored in IndexedDB on this device only. It does not sync. Use Settings > Export JSON backup regularly, and Import to restore.

## Known limits
No scheduled notifications and no per-topic difficulty rating. Data is per browser, so clearing site data erases it.

## Version 3 additions
Goals with deadlines and on-track check, 16-week focus heatmap, smart revision (forgot or partial recall adds another revision), light/dark theme, optional PIN screen, focus timer, daily check-in, sleep and wake consistency, weekly insight.

## Version 4 additions
Now/Next schedule card, Today's plan with a no-guilt recovery message, quick-add (+) button, global search, focus-timer goal alert, copy weekly report, backup reminder.

## Version 5 additions
Reminders (in-app alerts with sound, vibration, snooze; real phone alarms via .ics calendar export), energy quick-log, one-tap Mark done on tasks.

## Version 6 additions
Flashcards with spaced repetition, XP levels and badges (calculated from real records), focus sounds, CGPA and credit tracker, persistent storage request, automatic daily snapshots with restore, undo for deleted records.
