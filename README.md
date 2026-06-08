Local portfolio site — built without Webflow

Files added

- `index.html` — Home / Hero page
- `about.html` — About page
- `work.html` — Work / Case Studies page
- `skills.html` — Skills page
- `contact.html` — Contact page
- `assets/styles.css` — shared design tokens and component styles
- `assets/avatar.svg` — placeholder avatar image

Quick local preview

1. Open `portfolio-standalone.html` in your browser to preview the entire site in one file.
2. If open by double-clicking does not work, run a local server from this folder (Python 3):

```bash
cd "c:\Users\bsaki\Desktop\My portfolio"
python -m http.server 8000
# then open http://localhost:8000/index.html
```

How to use the files

- Edit any `.html` file directly in VS Code.
- Keep `assets/styles.css` in place for shared styling.
- Change the `href` links in the nav if you rename pages.
- Replace the placeholder LinkedIn link in `contact.html` when ready.

What is included

- A dark gradient portfolio design system.
- A homepage hero section with CTA buttons.
- An About page with your design mindset and quick facts.
- A Work page with real case study content.
- A Skills page with design, AI, and tool strengths.
- A Contact page with email and availability details.

Optional next steps

- Add real images or screenshots to the Work page.
- Replace the SVG avatar with your actual profile image.
- Add a contact form or host the site on Netlify / GitHub Pages.

### Non-Technical Deployment Option

If you prefer not to use terminal commands, use the browser-only guide in `NON-TECH-DEPLOY.md`.

### Browser-only GitHub + Vercel steps

1. Open GitHub and create a new repository: `bisola-portfolio`.
2. Upload all site files using GitHub's `Upload files` button.
3. Sign in to Vercel and import the repository.
4. Set the root directory to `/` and leave build/output settings blank.
5. Deploy and open the live URL.

If the site still shows `404`, make sure `index.html` is at the top level of the repo and no extra config file is blocking the build.

Do not upload `vercel.json` or any other Vercel config file for this simple static HTML site.

If you need help with the upload process, send me the GitHub repo URL and I will tell you exactly what to do next.