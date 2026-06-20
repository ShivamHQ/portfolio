# Shivam Mishra — Personal Portfolio

A single-page personal portfolio site for **Shivam Mishra**, Senior Manager — Product Analytics & Data Science.

Built as a single, dependency-free `index.html` (embedded CSS + vanilla JS) so it can be hosted anywhere with zero build step.

## Sections
- Hero with quick-stat highlights
- About
- Skills
- AI & Product Initiatives (REVKIN, Stock Picker)
- Professional experience timeline (Oportun, Google, PayPal, Myntra, LatentView)
- Education & awards
- Contact

## View locally
Just open `index.html` in any browser. Or serve it:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Pick the `main` branch and `/ (root)` folder, then **Save**.
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

> The included `.nojekyll` file tells GitHub Pages to skip Jekyll processing and serve files as-is.

## Résumé download
The hero has a **Download Résumé** button that links to `resume.pdf` in the repo root.
To enable it, place your resume PDF in this folder named exactly `resume.pdf`, then commit and push:

```bash
git add resume.pdf
git commit -m "Add resume PDF"
git push
```

## Customize
- All content lives in `index.html`. Edit the relevant section directly.
- Colors are CSS variables at the top of the `<style>` block (`--accent`, `--bg`, etc.).
- Replace the `SM` avatar initials with a real photo by swapping the `.avatar` `<div>` for an `<img>`.
