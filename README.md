# PhooD — Archive

A record of PhooD, a student-run research seminar series for Brandeis PhD students. Ran September 2024 – May 2026 across two academic years. Organized by Derrick Kim, James Petullo, Zepeng Hu, and Yifei Wang (PhooD 2.0).

**Live site:** https://euigyuki.github.io/phood2.0/

---

## What this is

A single-page archive of the program: what it was, when it ran, and every talk that took place. Meant as a static record.

The site is a single `index.html` file with no build step. All event data lives in the `EVENTS` array near the bottom of the file — update that if any details need to be corrected.

Each event has:
- `date` — `YYYY-MM-DD`
- `speaker` — the presenter's name (or `"Semester kickoff"` for openers with no formal speaker)
- `title` — optional talk title
- `abstract` — a sentence or two summarizing the talk; leave `""` if not recorded
- `attendance` — number of attendees, `"~N"` for a ballpark estimate, or `null` if not recorded

The Lamport Q&A is served as `lamport-questions.pdf` from the repo root.

---

## Local preview

Open `index.html` directly in a browser, or run:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
