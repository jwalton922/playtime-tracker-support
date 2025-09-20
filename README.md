# Playtime Tracker Support

This repository contains the support documentation for the Playtime Tracker iOS app.

## GitHub Pages Site

Visit the support site at: https://[YOUR-GITHUB-USERNAME].github.io/playtime-tracker-support/

## Setting Up GitHub Pages

1. Create a new repository on GitHub called `playtime-tracker-support`
2. Push this code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Support documentation"
   git branch -M main
   git remote add origin https://github.com/[YOUR-GITHUB-USERNAME]/playtime-tracker-support.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to Settings → Pages in your GitHub repository
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save
   - Your site will be available at `https://[YOUR-GITHUB-USERNAME].github.io/playtime-tracker-support/`

## Updating the Documentation

1. Edit the `index.html` file with your content
2. Update the GitHub username in the issue links
3. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Update documentation"
   git push
   ```

## Important Notes

- Replace `[YOUR-GITHUB-USERNAME]` with your actual GitHub username throughout the HTML
- The main Playtime Tracker repository should be created separately for issue tracking
- Consider adding a CNAME file if you want to use a custom domain

## File Structure

```
playtime-tracker-support/
├── index.html          # Main support page
├── README.md          # This file
└── .gitignore         # Git ignore file
```

## License

This documentation is part of the Playtime Tracker project.