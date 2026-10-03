# SmartTech Kerala website prototype

A responsive static HTML/CSS/JavaScript prototype for the Kerala branch.

## Files
- `index.html` — page structure and content
- `styles.css` — responsive layout and visual design
- `script.js` — mobile navigation, current year and demo-only form feedback
- `assets/smarttech-mark.svg` — original SVG brand mark

## Local preview
Open `index.html` in a browser.

## Cloudflare Pages
For a plain static site, use the repository root as the build output directory. Leave the build command blank or use `exit 0`, depending on the setup screen.

## Before public launch
- Confirm official Kerala phone number, WhatsApp number, email, and full business address.
- Confirm actual service areas and claims.
- Connect the enquiry form to a real backend/form service; the current form does not send or store data.
- Review privacy policy and consent requirements.
- The `/india/` URL on the existing domain requires routing configuration; deploying this repository to `pages.dev` alone will not create that path.
