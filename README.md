# Sumanth Reddy — Portfolio

Static site, no build step. Three files matter:

- `index.html` — the whole page (HTML, CSS and a few lines of JS inline)
- `portrait.jpg` — the photo shown in the sidebar
- `Sumanth_Reddy_Resume.pdf` — the résumé linked from the page

## Deploy to GitHub Pages

1. Replace the contents of the `Sumanth-s-Portfolio` repository with these files (keep them at the repository root).
2. Commit and push to `main`.
3. In the repository, open Settings → Pages. Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. The site is live at https://sumanth-reddy75.github.io/Sumanth-s-Portfolio/ within a few minutes.

## Updating content

- Project links: search `index.html` for `github.com/sumanth-reddy75` and point each row at its repository once it is public.
- Résumé: overwrite `Sumanth_Reddy_Resume.pdf`; the file name is referenced in three places.
- Photo: overwrite `portrait.jpg` (portrait orientation, around 640×800 works well).
- Open-to-work line, headline and contact details are plain text near the top of the file.

Fonts load from Google Fonts (Archivo and Source Serif 4) and fall back to system fonts offline.
