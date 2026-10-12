# Wenting Wang — Personal Portfolio

A complete, responsive, static personal website ready for **free GitHub Pages hosting**. No Node.js, build step, hosting subscription, or backend required.

## Files

- `index.html` — homepage with About, Résumé, Projects, Leadership, and Contact sections
- `resume.html` — printable résumé; click **Print / Save as PDF** in your browser
- `assets/styles.css` — responsive styles
- `assets/main.js` — accessible mobile navigation and current-year footer
- `assets/favicon.svg` — WW site icon
- `.nojekyll` — tells GitHub Pages to serve the files directly

## IMPORTANT: Personalize before going live

1. In `index.html`, replace `YOUR_EMAIL@example.com`, `YOUR_LINKEDIN`, and `YOUR_GITHUB_USERNAME` with your real links. Make the same changes in `resume.html`.
2. Review all experience statements, dates, projects and technical skills. Project cards explicitly describe *focus areas*, not confirmed deployed products. Replace with specific verified work samples when available.
3. Add your full prior employers, education, relevant dates, accomplishments and metrics to `resume.html` if you want to use it for applications.
4. Do **not** publish private phone numbers, employer-confidential information, internal code, or sensitive customer/system details.
5. Google Fonts are used for typography; the page will fall back to Arial when fonts are unavailable. Remove the first `@import` line in CSS if you prefer no external requests.

## Publish on GitHub Pages — free

1. Sign in to https://github.com and create a **public** repository named `YOUR_GITHUB_USERNAME.github.io`, replacing with your actual GitHub username.
2. Extract the ZIP file. Upload **all contents of the `wenting-portfolio` folder** into the repository root, retaining the `assets` subfolder. GitHub website: **Add file → Upload files → Commit changes**. Do not upload only the ZIP; GitHub Pages needs the extracted files.
3. Open **Settings → Pages**, then under **Build and deployment** choose **Deploy from a branch**. Pick `main`, `/ (root)`, and click **Save**.
4. After deployment, visit `https://YOUR_GITHUB_USERNAME.github.io/`.
5. For future edits, commit updated files; GitHub Pages will deploy the new version.

If your repository already has a site name other than `USERNAME.github.io`, Pages can still publish it at `https://USERNAME.github.io/REPOSITORY/` because this site uses relative asset paths.

## Local preview

Open `index.html` in a browser. For a local server (optional), run `python -m http.server 8000` from the project directory and visit http://localhost:8000/.

## Customize design

Edit the variables in `assets/styles.css` (`--navy`, `--blue`, etc.). All code is standard HTML, CSS, and vanilla JavaScript.

## Accessibility and SEO

Semantic HTML sections, proper headings, keyboard-visible focus, a skip link, mobile navigation state, and reduced-motion support are included. Before announcing your site, customize the title, description, and social metadata in `index.html`.
