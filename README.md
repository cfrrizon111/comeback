# Comeback OS V8 — Futuristic Foundation

A responsive, offline-first personal operating system for learning, career development and daily execution.

## Deploy on GitHub Pages
1. Export a JSON backup from the current installed app before upgrading.
2. Upload `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, and `icon-512.png` to the repository root.
3. In GitHub repository Settings → Pages, deploy from the `main` branch and `/ (root)`.
4. Open the published site in Chrome. The service worker cache is versioned `comeback-v8`; reload after deployment.

## V8 Phase 1 changes
- Futuristic dark visual system with responsive desktop sidebar and mobile bottom navigation.
- Existing modules and records retained; old sections remain available through navigation and All modules.
- New Career Command Center.
- New Skill Matrix, Job & Internship Pipeline, Interview Preparation, and Certificates modules.
- New collections are initialized when absent; existing IndexedDB collections are not deleted or renamed.
- Updated service-worker cache name and PWA metadata.
- Fixed weekly planned-versus-actual analytics to calculate planned time across each day’s schedule mode.

## Data and upgrade safety
Comeback OS stores records in IndexedDB on the current browser/device. It does not currently sync to a server. Export a JSON backup before deploying an update. This release retains the existing database name (`comeback`) and object store (`kv`) and adds new keys only. It does not migrate, clear, or overwrite existing records during startup.

## Important limitations
- The optional PIN is an interface lock, not encryption.
- Cloud sync, server-side authentication, AI integration and reliable background notifications are not included in Phase 1.
- Skill levels and career readiness are user-entered evidence trackers, not automated hiring predictions.
