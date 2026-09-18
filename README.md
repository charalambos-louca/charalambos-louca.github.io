# Charalambos Louca — academic website

Static academic website prepared for GitHub Pages.

## Intended public URL

https://charalambos-louca.github.io/

This package assumes your GitHub username is `charalambos-louca` and that the repository is named exactly:

`charalambos-louca.github.io`

If you use a different GitHub username, update the absolute URLs before publishing (canonical URLs, Open Graph URLs, structured data, `robots.txt`, and `sitemap.xml`).

## Publish with GitHub Pages

1. Create a GitHub account with the username `charalambos-louca` if it is available.
2. Create a **public** repository named exactly `charalambos-louca.github.io`.
3. Upload **the contents of this folder** to the root of the repository. `index.html` must sit at the repository root.
4. Commit the files to the `main` branch.
5. Open **Settings → Pages** in the repository.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select **main** and **/(root)**, then Save.
8. After GitHub finishes publishing, open https://charalambos-louca.github.io/ .

## Google Search Console

The existing Google verification meta tag is retained in `index.html`.

After the GitHub site is live:

1. Add `https://charalambos-louca.github.io/` in Google Search Console as a **URL-prefix** property.
2. Use **HTML tag** verification. The existing verification tag may verify the property; if Google gives you a different tag, replace the current `google-site-verification` tag in `index.html` with the new one.
3. Submit this sitemap:
   `https://charalambos-louca.github.io/sitemap.xml`
4. Request indexing for the homepage, Research page, and Publications page.

## SEO already updated for GitHub

The package has been updated so the GitHub Pages URL is used in:

- canonical URLs on every page
- Open Graph page URLs and image URLs
- JSON-LD structured data on the homepage
- `robots.txt`
- `sitemap.xml`

The sitemap `lastmod` date and homepage structured-data `dateModified` value are set to 18 September 2026.

## Files

- `index.html` — homepage
- `research.html` — research
- `publications.html` — publication record
- `about.html` — biography and selected collaborators
- `news.html` — recent activity
- `teaching.html` — teaching, mentoring, outreach and service
- `styles.css` — site styling
- `script.js` — navigation and page behaviour
- `assets/` — images and CV
- `sitemap.xml` — search-engine sitemap
- `robots.txt` — crawler instructions
- `.nojekyll` — tells GitHub Pages to serve the static files directly

## Important

Do not upload the enclosing ZIP itself into the repository. Extract it first and upload/commit the files inside the `charalambos-louca.github.io` folder.
