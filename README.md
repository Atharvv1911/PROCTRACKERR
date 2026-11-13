# Proctracker — iPhone-only starter

This is an installable Progressive Web App starter. It includes:
- Multiple exams with dates, priorities, preparation levels and syllabus topics
- Morning/night daily planning interview
- Flexible daily tuition attendance and focused-study logging
- Personal routine and medicine reminder list
- Meal/water/routine entries
- Daily checklist and end-of-day reflection
- Local browser storage on this device

## Important limitations of this starter
- Datesheet and syllabus files can be selected, but automatic OCR/PDF extraction is not implemented.
- The generated plan creates a prioritised task sequence, not a fully optimised hour-by-hour calendar.
- iOS web apps have limitations with background notifications. Use Apple Reminders/Clock for important medicine alerts.
- Data stays in this browser's local storage. Clearing Safari website data can erase it. This starter does not yet include export/import backup.
- It does not sync to other devices.

## Publish from iPhone using GitHub Pages
1. Extract the ZIP in the iPhone Files app.
2. Create a GitHub repository named `proctracker`.
3. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
4. In repository Settings → Pages, choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
5. Open the published URL in Safari → Share → Add to Home Screen.

Use HTTPS (GitHub Pages provides it) for service worker installation.
