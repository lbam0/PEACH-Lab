# PEACH Lab

A bilingual, responsive landing page for the PEACH Lab student research collective. The site is intentionally dependency-free and uses CSS/SVG motion, scroll reveals, a scroll progress indicator, and a language toggle.

## Customize

- Edit `index.html` to update the lab introduction, research themes, member biographies, contact details, and English/Chinese copy.
- Replace each `.portrait-placeholder` block with an image, such as `<img src="assets/liu.jpg" alt="刘丛竹">`.
- Keep both `data-en` and `data-zh` values when changing bilingual text.
- The motion respects the visitor's reduced-motion accessibility preference.

## Publish

The GitHub Actions workflow deploys the static site to GitHub Pages whenever changes are pushed to `main`. Set **Settings → Pages → Build and deployment → Source** to **GitHub Actions** once if Pages has not yet been enabled for the repository.
