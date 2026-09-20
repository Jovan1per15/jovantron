# Portfolio starter site

A 4-page static portfolio: `index.html`, `about.html`, `projects.html`, `contact.html`, sharing `style.css` and `script.js`.

## Deploy on GitHub Pages

1. Copy these files into the root of your GitHub repo (or into a `/docs` folder if you'd rather keep them separate).
2. Commit and push.
3. In the repo, go to **Settings → Pages**, set **Source** to "Deploy from a branch," pick your branch and folder, and save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## What to customize first

- **Name and copy**: replace "Jordan Lee" and all placeholder bio/project text with your own. Search for it across all four files.
- **Projects**: each project is a `.work-card` in `index.html` and `projects.html`. Swap the placeholder color blocks (`.work-thumb`) for real image tags: `<img src="images/project-1.jpg" alt="...">`.
- **Contact form**: the form in `contact.html` doesn't send anywhere yet. Easiest fix is a free service like Formspree or Getform — sign up, then paste the endpoint they give you into the form's `action` attribute.
- **Colors and type**: all defined once at the top of `style.css` under `:root` — change the hex values there to re-theme the whole site.
- **Favicon / social preview**: not included yet — add a `favicon.ico` and an Open Graph image if you want one.

## Notes

- No build step or dependencies — it's plain HTML/CSS/JS, so it works as-is on GitHub Pages.
- Fonts (Space Grotesk + Inter) load from Google Fonts via a CDN link in each page's `<head>`.
- Mobile nav collapses under 640px width; the toggle logic lives in `script.js`.
