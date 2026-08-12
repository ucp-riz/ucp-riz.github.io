# Muhammad Rizwan — Research Website

A static academic portfolio prepared from the supplied CV. It is ready for GitHub Pages and does not require a framework, database, or build step.

## Files

- `index.html` — profile content
- `style.css` — responsive academic styling
- `script.js` — mobile menu, smooth navigation, and automatic footer year
- `.nojekyll` — tells GitHub Pages to serve the static files without Jekyll processing
- `assets/Muhammad_Rizwan_CV.pdf` — supplied CV
- `assets/profile-placeholder.svg` — initials placeholder; replace with a professional photograph if desired
- `assets/favicon.svg` — browser tab icon
- `instructions/GitHub_Pages_Deployment_Guide.docx` — detailed Windows/VS Code/Git/GitHub Pages walkthrough

## Before publishing

1. Replace `assets/profile-placeholder.svg` with a professional photograph if desired. If you use `profile.jpg`, update the `<img>` path in `index.html`.
2. Add real GitHub, Google Scholar, ORCID, and LinkedIn links in the Contact section. These URLs were not visible in the supplied CV, so they were not invented.
3. Review all publication statuses before making the site public.
4. Review source spellings. The supplied CV includes `BuetifulSoup`, `LOUD FORECASTING`, and `PBTE SCHOLASHIP`; this package preserves those source spellings rather than silently changing them.
5. The phone number from the supplied CV is intentionally not displayed on the public webpage. Add it only if you deliberately want it public.

## Quick local preview

From this folder in VS Code terminal:

```bash
python -m http.server 8000
```

Open `http://localhost:8000` in a browser. Stop the server with `Ctrl+C`.

## GitHub Pages repository

For a personal GitHub Pages site, create a repository named exactly:

```text
YOUR-USERNAME.github.io
```

Then push these files to the `main` branch and configure GitHub Pages to deploy from `main` and `/(root)`.

See the DOCX guide in the `instructions` folder for the complete workflow and troubleshooting steps.
