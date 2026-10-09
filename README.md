# Academic Website — Prof. Esam A. Al-Qaralleh

A simple, responsive static academic website designed for GitHub Pages. No build tools or paid services are required.

## Files
- `index.html` — biography and portrait
- `courses.html` — course listing
- `publications.html` — publications from the supplied CV
- 13 standalone course HTML pages in **the same directory as index.html**
- `style.css`, `profile.jpg`, `favicon.svg`

## Publish on GitHub Pages
1. Create a **public** GitHub repository named `YOUR_USERNAME.github.io` (replace `YOUR_USERNAME` with your GitHub username).
2. Upload **all files in this folder** to the repository root. Do not upload the ZIP itself.
3. In repository **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/ (root)` and save (if not already configured).
4. Your website will appear at `https://YOUR_USERNAME.github.io/` once GitHub finishes deployment.
5. For a custom domain, configure DNS and the domain in Settings → Pages.

You can also publish from any public repository as a project site; relative links here support either option.

## Edit
- Update bio and links in `index.html`.
- Update course list in `courses.html` and matching individual course pages.
- Update bibliography in `publications.html`.
- Change colors and typography in `style.css`.
- Replace `profile.jpg` with a photo of the same filename.

## Accuracy notes
- Course descriptions are concise, original summaries, not official PSUT catalog text.
- The CV contains a separate section 'Courses I Can Teach and Contribute to'; those items were not automatically treated as courses previously taught.
- The publication entries are from the provided CV, not verified against journal databases. A stray standalone 'March 2012.' artifact was omitted from the conference list.
- Contact email and Google Scholar link come from the supplied CV.