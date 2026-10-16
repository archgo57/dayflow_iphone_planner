# Dayflow — Daily and Weekly Planner

## Publish / update on GitHub Pages
1. Extract this ZIP.
2. Upload `index.html`, `manifest.json`, and `sw.js` to the root of your existing repository, replacing the old files.
3. Commit the changes.
4. Keep GitHub Pages configured to deploy from `main` and `/(root)`.
5. Open your existing Pages URL. If an older version appears, hard refresh or clear the browser cache.

## Included in this version
- Daily timeline and weekly overview
- Add, edit, complete, and delete tasks
- Date, start time, duration, category, priority, repeat setting, notes, and fixed commitments
- Routine shortcuts
- Daily progress summary and category filters
- Local device storage and JSON backup export
- Responsive layout for iPhone and desktop; PWA manifest/service worker

## Important limits
This is a frontend planner. Tasks are stored in the browser on the device and do not automatically sync between devices. Recurrence is stored as a setting but does not yet auto-create future task instances. The app does not yet intelligently reschedule conflicting tasks, sync with calendars, or send push notifications; those are subsequent implementation steps. Do not rely on this version for critical reminders.
