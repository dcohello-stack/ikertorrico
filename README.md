# Iker Torrico — University Application Portfolio

A clean, modern, responsive single-page portfolio built with plain **HTML, CSS, and JavaScript** — no frameworks, no build step, ready to deploy anywhere.

## Files

| File         | Purpose                                        |
| ------------ | ---------------------------------------------- |
| `index.html` | All content and sections                       |
| `styles.css` | Design system, colors, responsive layout       |
| `script.js`  | Navigation, scrollspy, animations, counters    |

## Run locally

Just double-click `index.html`, or serve it (recommended, so fonts and smooth scrolling behave exactly like production):

```bash
# any static server, e.g.
npx http-server portfolio -p 8080
# or
python -m http.server 8080 --directory portfolio
```

Then open <http://localhost:8080>.

## Deploy

- **Vercel / Netlify:** drag-and-drop the `portfolio` folder into a new project, or connect the repo — zero config.
- **GitHub Pages:** push the folder to a repo → Settings → Pages → deploy from branch.

## Editing content

- **Text & achievements:** everything lives in clearly-marked sections in `index.html` (`HERO`, `ABOUT`, `01 · SPORTS & COMPETITION`, `02 · PEOPLE & COMMUNITY`, `03 · BUSINESS & BIG IDEAS`, `04 · GUITAR & PERFORMANCES`, `EDUCATION & HONORS`, `WHAT'S NEXT`, `CONTACT`).
- **Colors:** change the CSS variables at the top of `styles.css` (`:root`).
- **Hero stats:** the four numbers are `data-target` attributes in `.hero-stats` (`index.html`).
- **Photo:** the hero shows an "IT" monogram avatar (`.hero-card-avatar`). To use a real photo, replace that element's content with `<img src="photo.jpg" alt="Portrait of Iker Torrico" />` and add `img { width: 100%; height: 100%; object-fit: cover; border-radius: 50%; }` inside the avatar rule.

> **Note:** All copy is based on Iker's résumé and draft website text (`Reesume.docx`, `Iker Torrico - Web Txt.docx`). Double-check dates, figures, and phrasing before publishing — especially the Panini sales numbers, Operation Smile fundraising amounts, and internship dates.

## Design palette

| Token          | Hex       | Use                          |
| -------------- | --------- | ---------------------------- |
| Deep Navy      | `#0F3D66` | Primary — headings, dark UI  |
| Ocean Blue     | `#4F8BC9` | Accents, links, gradients    |
| Sky Light Blue | `#A7D8F0` | Secondary text on dark       |
| Mint Green     | `#BFE866` | CTAs, highlights             |
| Light Cloud    | `#F4F8FB` | Section backgrounds          |
