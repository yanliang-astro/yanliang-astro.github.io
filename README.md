# Yan Liang — academic website

This package is ready for the public GitHub repository `yanliang-astro/yanliang-astro.github.io`.

## Upload and publish

1. Extract the ZIP on your computer.
2. In your GitHub repository, open **Add file → Upload files**.
3. Upload `index.html`, the complete `assets` folder, `.nojekyll`, and this `README.md` to the top level of the `main` branch. Replace the placeholder `index.html` and README if present. Upload the extracted contents, not the ZIP or its enclosing folder.
4. Commit the changes.
5. Open **Settings → Pages**. Select **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**. If these settings are already selected, leave them as they are.
6. Check the deployment in the Actions tab. Once it succeeds, visit https://yanliang-astro.github.io/ . Publication can take up to 10 minutes.

The `.nojekyll` file is intentionally empty. It tells GitHub to serve this static site without Jekyll processing. On macOS, press Command–Shift–period in Finder to show hidden files. Alternatively, use **Add file → Create new file** in GitHub, name the file `.nojekyll`, and commit it.

## Files

- `index.html`: homepage, biography, publication list, contact information.
- `assets/style.css`: layout, colors, and typography.
- `assets/yan-liang.jpg`: portrait.
- `assets/Yan-Liang-CV.pdf`: downloadable CV.
- `assets/InterVariable.woff2` and `assets/InterVariable-Italic.woff2`: self-hosted Inter fonts.
- `assets/Inter-LICENSE.txt`: font license.
- `assets/favicon.svg`: browser tab icon.
- `.nojekyll`: GitHub Pages configuration.
- `README.md`: these instructions; not displayed on the homepage.

No installation, build step, database, or server-side code is required. Committing changes to the published branch updates the website automatically.

## Maintenance

Edit the bio and publications in `index.html`. Replace `assets/Yan-Liang-CV.pdf` to update the CV while preserving its download link. The AESTRA II status is recorded as under review in October 2026; update it when appropriate.

The page uses the current approved biography, the headline “Astrophysics & AI,” seven papers from 2022 onward, and the light grey / Inter design. The upper-left duplicate name label is removed. The social preview image URL points to the GitHub Pages domain.

## Credits

Portrait: https://www.hsfoundation.org/fellow/yan-liang/
Image source: https://www.hsfoundation.org/wp-content/uploads/Yan-Liang-Profile.jpg
Fonts: Inter, https://rsms.me/inter/ (license included).
