# Security Notes (Jekyll site for GitHub Pages)

## Publish in 5 steps
1. Create a GitHub account with a professional username (e.g. `hojae-kim`).
2. Create a new **public** repository named exactly `YOUR-USERNAME.github.io`. 
3. Upload every file and folder from this zip (Add file > Upload files), then Commit.
4. Settings > Pages > Build and deployment: Source = "Deploy from a branch", Branch = `main`, folder `/ (root)`. Save.
5. Wait 1 to 3 minutes, then open https://YOUR-USERNAME.github.io

## Before publishing
- Replace `YOUR-USERNAME` and `YOUR-LINKEDIN-ID` in `_config.yml` and `about.md`.
- Rewrite `_posts/2026-11-15-starting-this-log.md` in your own words.

## Writing a new post
1. Copy `_templates/daily-note.md` into `_posts/`.
2. Rename it `YYYY-MM-DD-short-title.md` (e.g. `2026-11-16-osi-model.md`).
3. Fill it in. Use `categories: [lab]`, `[grc]` or `[francais]` to show it on those pages.
4. Commit. The site updates in about a minute.

Drafts you are not ready to publish can sit in `_drafts/` (they are not published).
