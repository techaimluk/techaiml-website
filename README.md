# TechAIML Website

Jekyll website for [www.techaiml.co.uk](https://www.techaiml.co.uk) — IoT solutions for agriculture and BolusAI, the smart rumen capsule for cattle heat detection and health monitoring.

Hosted free on **GitHub Pages** (builds Jekyll automatically — no local setup needed).

## Structure

- `index.html` — home page
- `services.html`, `bolusai.html`, `about.html`, `contact.html` — inner pages
- `_layouts/default.html` — shared layout (header/footer)
- `assets/css/style.css` — all styling
- `_config.yml` — site settings
- `CNAME` — custom domain for GitHub Pages

## One remaining setup step

The contact form uses [Formspree](https://formspree.io) (free). Sign up, create a form, and replace `YOUR_FORM_ID` in `contact.html` with your form ID.
