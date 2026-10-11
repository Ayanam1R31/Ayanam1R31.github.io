# Ayanam1R31.github.io
Owen Maute's portfolio website, built with plain HTML and CSS and hosted on GitHub Pages at https://ayanam1r31.github.io

## Structure
- `index.html`: home page (hero, project tiles, about, experience, recognition, contact)
- `projects/`: one page per project
- `css/styles.css`: styles; colors and fonts are variables at the top
- `js/main.js`: footer year and mobile menu
- `assets/images/<project>/`: photos for each project, plus `home/` for the home hero
- `.github/workflows/deploy.yml`: publishes the site on every push to `main`

## Adding a photo
Put the file in the project's folder under `assets/images/`, then add a `<figure>` to the `gallery` section of that project's page. Add `class="wide"` for a full-width photo or `class="tall"` for a portrait one.

## Preview locally
Open `index.html` in a browser. No build step.
