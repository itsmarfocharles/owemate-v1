# OweMate

Free mobile-first PWA for organizing money owed to people and businesses.

## Features
- People/business records
- Amount owed and amount paid
- Remaining balance and payment progress
- Due dates and countdown status
- Due soon / overdue / paid filters
- Search
- Phone and notes
- Add/edit/delete records
- Browser notifications
- `beforeinstallprompt` install flow
- Offline service worker
- JSON export/import backup
- No backend or monthly database cost

## GitHub Pages
Upload all four files plus this README to the repository root. Then use **Settings → Pages → Deploy from a branch → main → /(root)**.

## Cloudflare Pages
Connect the GitHub repository. No build command is needed; use the repository root as the output directory.

## Reminder limitation
This free static version checks reminders while the app is open/active. A browser cannot guarantee waking a completely closed app at a future date on every phone. Guaranteed background push notifications require a push backend later.

## Privacy
Records are stored locally in the user's browser. There is no account or database in this version. Export a backup before clearing browser data or changing devices.
