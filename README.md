# Bryce Milbank Development — Portfolio Website

A custom responsive portfolio built with HTML5, CSS3 and vanilla JavaScript. No frameworks, accounts or build tools required.

## Open locally

1. Unzip the folder.
2. Double-click `index.html` to open it in your browser.
3. For a development server (optional), open a terminal inside the folder and run `python -m http.server 8000`, then visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a public GitHub repository (for example `bryce-portfolio`).
2. Upload **the contents of this folder** to the repository root (so `index.html` is at the root).
3. In the repository, open Settings > Pages and select **Deploy from a branch**, `main`, `/ (root)`.
4. Once published, add your public GitHub and LinkedIn URLs to the page.

The site uses relative links, so it works both at a custom domain and at a GitHub Pages repository URL.

## What is functional

- Responsive navigation with mobile menu and Escape-key support
- Project category filters (all, full-stack, mobile, research/security)
- Four dedicated project case studies accessible from project cards
- Light / dark theme switch, stored locally in the browser
- Scroll reveal animations with reduced-motion accessibility support
- Copy email button (requires a supported browser context)
- Email contact links and downloadable Word CV

## Important finishing steps before publishing

- Replace the illustrative project graphics with your **real project screenshots**, and consider adding carefully vetted demo/repository links. Do not publish Supabase secrets, production configuration, personal data, private stakeholder information or proprietary assets.
- Review all project descriptions for accuracy and update them as your projects evolve.
- Replace `assets/docs/Bryce-Milbank-CV.docx` when your CV is final. You can add a PDF version and adjust CV links if desired.
- Edit the contact email in `index.html` and the `data-copy` attribute if it changes.
- Add real GitHub and LinkedIn URLs when you are ready. Deliberately **no fictitious or dead social links** are included.
- Replace the concept brand with your final brand name when decided.
- The portrait is an edited image supplied in this conversation. Replace with a current photo if preferred.
- Google Fonts need an internet connection; local fallbacks are specified.

## Files

- `index.html`: Homepage, projects, skills, about, contact
- `project.html`: Generic project detail page
- `js/main.js`: Theme, filtering, menu, copy email and animations
- `js/projects.js`: Editable content for all four project pages
- `css/style.css`: Styles and responsive breakpoints
- `assets/img/`: Portrait and favicon
- `assets/docs/`: Editable CV

## Change projects

Edit the `projects` object in `js/projects.js` to update detail content. Homepage project summaries and artwork are in `index.html`.

Note: the illustrations on project cards are creative mockups, **not actual screenshots** of LensFlow, TestNest, or coursework environments.

## LensFlow project screenshots (V1 personalisation)

The LensFlow project card and case study now feature five screenshots supplied by the author. Images are stored in `assets/img/lensflow/` as web-optimised WebP files. Select any screenshot in the LensFlow case study to open the keyboard-accessible viewer (Escape closes, arrow keys move between images).

Before publishing the site publicly, review screenshots for names, booking details, contact information, images, or other data requiring permission, even if examples were created for testing.

## TestNest screenshots

The TestNest card and its case study use five real screenshots from the web and Android applications. The student ID visible in one original screenshot has been concealed in the public portfolio copy.
