# Holy Name Prenatal Packet app

Static site — no build step, no server code.

## Deploy on Netlify
1. Go to app.netlify.com → "Add new site" → "Deploy manually".
2. Drag this whole folder (the one containing index.html) onto the page.
3. Netlify gives a URL immediately; a custom domain can be added under Site settings → Domain management.

## Deploy on GitHub Pages
1. Create a repository and upload every file in this folder (keep the `content/` and `img/` folders).
2. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The site appears at https://<user>.github.io/<repo>/ within a few minutes.

## Updating content
Each language is a JSON file in `content/` (en, es, ko, ht). Practice rosters, phone numbers, offices, and cover letter text are in the `PRACTICES` and `STR` objects near the top of the script in index.html. The doctor list is the `DOCTORS` array.
