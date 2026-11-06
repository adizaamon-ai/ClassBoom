# ClassBloom 🌸

**Every Student Has a Story. Every Improvement Matters.**

ClassBloom is a teacher-only student performance journal. The teacher enters marks; the app calculates weighted scores, rankings, XP, levels and badges, and shows each student's progress over time. Students never log in.

> **Prototype status:** this version is a single static page. All data is saved in the browser's local storage on one device. It has no login, so **do not enter real student records.** See the roadmap below for the production version.

## Features
- Classrooms and students
- Spreadsheet-style evaluation journal with draft, preview and publish (published evaluations are locked)
- Mark entry: `0-100`, `N` = not submitted (counts as 0, flagged), `A` = absent, blank = not evaluated (both excluded from averages)
- Configurable grading weights (default 20/20/20/30/10)
- Leaderboard with crown, silver and bronze ranks, XP and levels
- Auto-awarded badges: Perfect Star, Homework Hero, Rising Star
- Student profile with a clickable performance chart
- Private "needs attention" suggestions on the dashboard
- Light and dark themes, demo data you can remove

## Run locally
Open `index.html` in a browser. No build step.

## Publish with GitHub Pages
1. Create a new repository on GitHub and upload all files from this folder.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

## Roadmap (production version)
- Teacher login and a real database (for example Supabase with row-level security)
- Student photo upload with private storage
- Correction log for published evaluations (original value, new value, date, reason)
- Calendar heatmap, skill radar, Hall of Fame, private notes
- Reports and certificates, CSV/Excel/PDF export, import and backup

## License
MIT
