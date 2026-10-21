# Picta Photo Books: Perception Audit

Standalone page for my PMM portfolio. One file, no build step: `index.html`
(fonts load from Google Fonts; everything else is inline).

## Before you publish
- Replace the six sample quotes (search `PLACEHOLDER` in `index.html`) with your Apify results and update the source captions.
- Update scores and bubble tooltips (`<title>` tags inside the two `<svg>` maps) if the scrape changes them.

## Option A: add to your existing portfolio repo (recommended)
1. Open your portfolio repo on github.com.
2. Click **Add file → Create new file**.
3. In the name box type `picta-perception-audit/index.html` (the slash creates the folder).
4. Open `index.html` from this folder in a text editor, copy everything, paste it into GitHub.
5. Click **Commit changes** (commit directly to `main`).
6. If Pages is already on for the repo, wait 1-2 minutes. The page lives at
   `https://YOUR-USERNAME.github.io/YOUR-REPO/picta-perception-audit/`

## Option B: new repo just for this page
1. github.com → **New repository** (e.g. `picta-perception-audit`), Public, tick **Add a README**.
2. **Add file → Upload files**, drag in `index.html`, then **Commit changes**.
3. **Settings → Pages**: Source = **Deploy from a branch**, Branch = `main`, folder = `/ (root)`, **Save**.
4. After 1-2 minutes the page is live at `https://YOUR-USERNAME.github.io/picta-perception-audit/`

## Command line (optional)
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
mkdir picta-perception-audit
cp /path/to/index.html picta-perception-audit/
git add . && git commit -m "Add Picta perception audit" && git push
```

## Then
- Paste the live URL into the "Value Benchmarking Study" link on your portfolio (replacing "Coming soon").
- Check it on your phone. Hover tooltips on the maps are desktop only.
- Pages caches for a few minutes. Hard refresh if an edit doesn't show.
