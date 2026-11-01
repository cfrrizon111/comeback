# The Comeback Project — Android-installable scheduler

This is a self-contained Progressive Web App (PWA) for Fardin's personal study routine.

## Included
- Daily timetable and completion checklist
- Daily logs: wake/sleep, focused hours, mood, what was learned, what was missed, reasons, questions and tomorrow's plan
- Learning journal with subject, topic, notes, evidence and understanding level
- Pending/missed task list with priority and rescheduling date
- Analytics for study hours, averages, logged days and subject entries
- JSON backup/restore and CSV export
- Offline cache after the first successful load

## Install on Android
A PWA must be served from HTTPS (or localhost) to install and use its service worker. This source ZIP is not an APK and is not yet hosted.

1. Upload the contents of this folder to a static HTTPS host, such as a GitHub Pages repository.
2. Open the hosted `index.html` URL in Chrome on Android.
3. Open Chrome's ⋮ menu and choose **Install app** or **Add to Home screen**.
4. Open the installed app. Export a JSON backup regularly.

## Data and privacy
Records are stored in browser localStorage on the device. They do not sync automatically between devices and may be lost if browser data is cleared. Use **Backup → Export all data (JSON)** regularly. Importing a backup replaces the current local dataset.

## Important
- This prototype uses the routine agreed in the conversation: 10:30 AM wake-up, 1:30 AM bedtime, 8–9 hours study, Python + Data Science + AI, and ongoing trading education.
- Weekend and alternate-Wednesday class times are not hard-coded because exact class timings were not provided.
- The app does not send reminders or notifications yet.
