# PhooD — Archive

A record of PhooD, a student-run research seminar series for Brandeis PhD students. Ran September 2024 – May 2026 across two academic years. Organized by Derrick Kim, James [—], and Zepeng [—].

**Live site:** `https://<username>.github.io/phood/`

---

## What this is

A single-page archive of the program: what it was, when it ran, and every talk that took place. Meant as a static record.

The site is a single `index.html` file with no build step. All event data lives in the `EVENTS` array near the bottom of the file — update that if any details need to be corrected.

Each event has:
- `date` — `YYYY-MM-DD`
- `speaker` — the presenter's name (or `"Semester kickoff"` for openers with no formal speaker)
- `restaurant` — where the food was ordered from; leave `""` if not recorded
- `attendance` — number of attendees, or `null` if not recorded

---

## Publishing

1. Create a new repo on GitHub named `phood` under your account.
2. Push `index.html` (and this README) to the `main` branch.
3. In the repo, go to **Settings → Pages**.
4. Under **Source**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save.
5. The site will publish to `https://<username>.github.io/phood/` within a minute.

Independent of any other repos on the same account — GitHub Pages project sites don't share state.

---

## Local preview

Open `index.html` directly in a browser, or run:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
