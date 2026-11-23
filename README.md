# Jose Romero — Portfolio

Personal portfolio for Jose Romero, a software developer, mentor, and pitch presenter based in Milwaukee, WI. Built with plain HTML, CSS, and a little vanilla JavaScript, and hosted on GitHub Pages.

## What's on the site
- **Hero** — intro, call-to-action buttons, and a stats strip (400+ CS students mentored, 1 of 4 teams won the pitch, 3 orgs, 10-week Python course).
- **About** — background, career path, and a skills list (HTML, CSS, JavaScript, TypeScript, Git & GitHub, Java, MySQL, Python, Data Structures & Algorithms, Wireframing, Code Review, Technical Mentoring).
- **Experience** — timeline of roles:
  - Intern, i.c.stars (Aug 2026 – Present)
  - Tech Fellow, CodePath (Jan 2025 – Feb 2026)
  - Account Coordinator, The Trade Desk (Jun 2022 – Aug 2023)
- **Projects** — Affirmation Generator (HTML/CSS/JS), Scrunch (Java), and Oro (Java, in development).
- **Contact** — email, GitHub, and LinkedIn links.

## Files
- `index.html` — page content and the small script for scroll-reveal and count-up numbers
- `styles.css` — all styling; colors are defined as variables under `:root` at the top
- `README.md` — this file

## Run locally
No build step or dependencies. Open `index.html` in a browser, edit, save, and refresh. Or serve the folder:

```
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Editing tips
- **Experience:** copy a `<li class="job">` block in the `timeline` list and update the title, company, dates, bullets, and tags.
- **Projects:** copy an `<article class="project-card">` inside `project-grid`.
- **Stats:** numbers with a `data-count` attribute animate on load; `data-suffix` adds trailing text (e.g. `+`).
- **Colors:** change the variables under `:root` in `styles.css`.
- **Accessibility:** the animations are skipped when the visitor has `prefers-reduced-motion` enabled, and the page works without JavaScript.

## Deployment
The site is served by GitHub Pages from the `main` branch, `/ (root)` folder (**Settings → Pages**). The repo must be named `<username>.github.io` for the site to be served at the root URL. Pushes to `main` go live within a minute or two.

## Conventions
- Write clear commit messages that say what changed (`Update about section`, not `stuff`).
- Keep filenames lowercase with no spaces.
- Commit small and often.

## Contact
[Email](mailto:josedanilromero@gmail.com) · [GitHub](https://github.com/jdrome) · [LinkedIn](https://linkedin.com/in/josedanilromero)
