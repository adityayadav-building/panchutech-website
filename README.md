# PanchuTech Cine Systems website

Static website for PanchuTech Cine Systems Pvt. Ltd., a cinema and home theater engineering company based in New Delhi.

## Pages

- `index.html` - home
- `services.html` - the six engineering disciplines
- `work.html` - completed auditoriums and walkthrough video
- `engineering.html` - process and design references
- `about.html` - company, mission and the Cine Aryan collaboration
- `contact.html` - enquiry form and contact details

All pages share `style.css`. Images and video live in `assets/`.

## Run locally

No build step. Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000

then visit http://localhost:8000.

## Deploy with GitHub Pages

1. Push this repository to GitHub.
2. Go to Settings > Pages.
3. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`.
4. The site will be live at `https://<your-username>.github.io/<repo-name>/`.

## To do before going live

- Replace the placeholder phone number and email on the contact page.
- Connect the enquiry form to a real backend (Formspree or similar). It currently only shows a confirmation alert.
- Replace the recreated P mark with the original vector logo file.
