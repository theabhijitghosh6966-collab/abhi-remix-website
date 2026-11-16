# ABHI REMIX — Gold Premium Website

This repository contains the static public website files for ABHI REMIX.

## Upload to GitHub
1. Extract the ZIP archive on your device.
2. Open your existing GitHub repository.
3. Choose **Add file → Upload files**.
4. Upload the extracted website contents (including `index.html`, `admin.html`, `assets/`, `songs/`, and other existing files). Do not upload the ZIP itself as the website source.
5. Commit the changes to the branch connected to Vercel.

Keep the existing repository and its deployment settings. Do not delete song folders, assets, or setup files.

## Vercel
If this repository is already connected to Vercel, a commit to its production branch should trigger a deployment automatically. Check the Vercel deployment status before considering the live site updated.

## Notes
- This is a static website bundle; keep `index.html` at the repository root.
- `.gitignore` excludes local secrets and tooling folders.
- Never commit private API keys, passwords, or `.env` files.
