# Lendr Static Website

This directory contains the static website for Lendr, designed for hosting on **GitHub Pages**.

## Files Included

- `index.html`: Landing page.
- `privacy.html`: Privacy Policy (compliant with Google Play requirements).
- `delete-account.html`: External account deletion request page (compliant with Google Play requirements).
- `support.html`: Support and contact page.
- `styles.css`: Custom responsive styling.
- `assets/`: Logos, icons, and favicon.

## How to Publish

### Option 1: Separate Repository (Recommended)

1. Create a new public repository on GitHub (e.g., `lendr-site`).
2. Copy the contents of this `/lendr-site/` folder into your new local repository.
3. Commit and push the files to the `main` branch.
4. In your GitHub repository settings, go to **Pages**.
5. Under **Build and deployment**, set the source to **Deploy from a branch** and select the `main` branch (root folder).
6. Your site will be available at `https://<username>.github.io/lendr-site/`.

### Option 2: Main Project Repository

If you want to keep the site in your main Android project repository:

1. Push the `/lendr-site/` directory to your repository.
2. In GitHub repository settings -> **Pages**, set the source to **Deploy from a branch**.
3. Select your branch and the `/lendr-site` folder.
4. Your site will be available at `https://<username>.github.io/Lendr/lendr-site/`.

## Design Notes

- **Zero Trackers:** No analytics, cookies, or advertising scripts are included.
- **Privacy-First:** The privacy policy is based on the actual codebase audit of the Lendr app.
- **Responsive:** The site is tested for mobile and desktop browsers.
- **Relative Links:** All internal links use relative paths so the site works correctly in subdirectories or custom domains.
