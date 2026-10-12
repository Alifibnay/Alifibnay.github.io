# Alif Ibnay — Portfolio

Static portfolio site (HTML, CSS, vanilla JavaScript). No build step.

## Run locally
Open `index.html` in a browser (internet needed for Google Fonts and Matter.js from a CDN).

## Structure
- `index.html` — page markup (hero, about, skills playground, projects, experience, certificates, testimonials, contact)
- `css/style.css` — all styles and animations
- `js/main.js` — content data, scroll effects, photo upload, project carousel, physics playground

## Edit your content (top of `js/main.js`)
- `LINKS` — paste your Facebook / LinkedIn / GitHub URLs; WhatsApp = number with country code (e.g. `8801XXXXXXXXX`)
- `EDU`, `ACH` — education and achievements
- `PJ` — projects
- `EX` — experience (replace the "Add period" / "Add company" placeholders)
- `SK` — playground skill blocks

## Photo
Click the circle in the About section to upload a photo (saved in that browser only). To show it for everyone, add an image file and set it as the background of `#av` in `css/style.css`.

## Deploy
Drag the `alif-portfolio` folder onto https://app.netlify.com/drop (or use GitHub Pages / Vercel).
