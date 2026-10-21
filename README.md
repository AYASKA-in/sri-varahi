# Sri Varahi – promotional site (GitHub Pages)

One static page: `index.html`, `mark.svg`, `og.png` (share image), `robots.txt`, `sitemap.xml`, `.nojekyll`.

## Publish on GitHub Pages
1. On GitHub, create a new public repository named `sri-varahi` under `AYASKA-in`.
2. Upload every file in this folder (including `.nojekyll`) to the repository root.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)` → Save.
4. After a minute the site is at https://ayaska-in.github.io/sri-varahi/

If the repository or account name is different, replace `https://ayaska-in.github.io/sri-varahi/`
in `index.html`, `robots.txt` and `sitemap.xml` with the real address (it is used for search engines
and link previews). For a custom domain later, add a `CNAME` file with the domain.

## Search engines
Add the address in Google Search Console and submit `sitemap.xml`.
The app itself (workers.dev) stays hidden from search engines until it moves to its live domain.
