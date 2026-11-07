# Schutz Family Tree website

Everything in this folder is the website. Open `index.html` in a browser to preview it on your own computer.

## Put it online with GitHub Pages

1. Sign in at github.com (or create a free account).
2. Click **+** (top right) → **New repository**. Name it something like `family-tree`. Leave it **Public** (free Pages sites need a public repository). Click **Create repository**.
3. On the new repository's page, click **uploading an existing file**. GitHub takes at most 100 files per upload, so do it in two rounds:
   - Round 1: drag in `index.html`, `data.js`, `stories.js`, `robots.txt`, `README.md`, and the `thumb` folder. Click **Commit changes**.
   - Round 2: click **Add file → Upload files**, drag in the `full` folder, and click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment," set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**. Click **Save**.
5. Wait a minute or two, then refresh that page. It shows your link: `https://YOUR-USERNAME.github.io/family-tree/`.

## Updating it later

Export a fresh GEDCOM from Ancestry and ask Claude to rebuild the site. Then replace `data.js` (and upload any new images into `full` and `thumb`) in the repository: **Add file → Upload files**, drag them in, **Commit changes**. The link stays the same.

## Adding stories and biographies

Open `stories.js` on GitHub and click the pencil icon to edit it. The instructions are at the top of the file. Each person's ID is at the bottom of their page and at the end of the page's web address. Click **Commit changes** when you're done; the site updates in a minute or two.

Rebuilding the site from a new Ancestry export never touches `stories.js`, so your writing is safe. If a typo in the file breaks it, the site still works; the stories just won't show until it's fixed.

## Privacy

- Living people show only as "Living," with no names, dates, places, or records.
- Social Security numbers that were in Ancestry source citations have been removed.
- The site asks search engines not to index it, but anyone with the link can open it.
