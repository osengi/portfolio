# Portfolio Site

Simple static HTML/CSS portfolio, hosted via GitHub Pages.

## Structure

- `index.html` — homepage / project list
- `hextronics.html` — Hextronics internship writeup
- `projects/project-template.html` — copy this file to add a new project page
- `assets/css/style.css` — shared stylesheet
- `assets/img/` — all images/media

## Adding a new project

1. Copy `projects/project-template.html` to `projects/your-project-name.html`.
2. Fill in the `<!-- UPDATE -->` sections.
3. Add a matching card to the `.project-grid` in `index.html`, linking to your new page.
4. Drop images into `assets/img/`.

## Publishing with GitHub Pages

1. Push this repo to GitHub.
2. In the repo settings, under Pages, set the source to the `main` branch, root folder.
3. Site will be live at `https://<username>.github.io/<repo-name>/`.
