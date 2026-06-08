
# Non-Technical GitHub + Vercel Deployment Guide

This guide is for people who prefer using the browser instead of terminal commands.

## Step 1: Create a GitHub repository

1. Open https://github.com and sign in.
2. Click the `+` icon in the top right and choose `New repository`.
3. Repository name: `bisola-portfolio`
4. Description (optional): `Portfolio site for Bisola Akinlabi`
5. Keep it Public or Private.
6. Do not add a README, .gitignore, or license on GitHub if you already have files locally.
7. Click `Create repository`.

## Step 2: Upload your site files to GitHub

1. On the new repository page, click `Add file` → `Upload files`.
2. Open your local folder in File Explorer:
   - `c:\Users\bsaki\Desktop\My portfolio`
3. Drag and drop everything from that folder into GitHub:
   - `index.html`
   - `about.html`
   - `work.html`
   - `skills.html`
   - `contact.html`
   - `assets/`
   - `README.md`
   - `.gitignore`
   - Do not upload `vercel.json` or any Vercel-specific config file.
4. Wait for GitHub to finish uploading.
5. In the `Commit changes` section, write a message like `Add portfolio site files`.
6. Click `Commit changes`.

## Step 3: Deploy to Vercel

1. Open https://vercel.com and sign in with GitHub.
2. Click `New Project`.
3. Choose the `bisola-portfolio` repository.
4. Vercel should detect it as a static site.
5. For settings:
   - Root Directory: `/` (leave empty if there is no input)
   - Build Command: leave blank
   - Output Directory: leave blank
6. Click `Deploy`.

## Step 4: Check the deployment

1. After deployment, Vercel will show a live URL.
2. Open the URL in your browser.
3. If your portfolio appears, it is deployed correctly.

## Common issues and fixes

### Issue: `404` page or site not found

This usually means Vercel is looking in the wrong folder.

Fix:
- In Vercel, open the project settings.
- Find `Root Directory` and make sure it is `/`.
- Redeploy.

### Issue: file paths not found

Make sure the `assets/` folder is in the repository root, next to `index.html`.

## If you want me to help remotely

Send me the GitHub repository URL and the Vercel live URL.
I can check the files and tell you exactly what to change.
