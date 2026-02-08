# How to Enable GitHub Pages

To make the webpage preview live, you need to enable GitHub Pages in your repository settings:

## Steps:

1. Go to your repository on GitHub: https://github.com/GeneralStokan/Hytale-Mods-To-Try

2. Click on **Settings** (in the top navigation bar)

3. In the left sidebar, click on **Pages** (under "Code and automation")

4. Under **Source**, select **GitHub Actions** from the dropdown

5. The workflow will automatically deploy your site when you merge this PR to the main branch

6. Once deployed, your webpage will be available at: 
   **https://generalstokan.github.io/Hytale-Mods-To-Try/**

## What Was Added:

- **`index.html`** - A beautiful, styled webpage that displays all your Hytale mods in an organized, user-friendly format with tables and categories
- **`.github/workflows/pages.yml`** - GitHub Actions workflow that automatically deploys your site to GitHub Pages
- **Updated `README.md`** - Added a prominent link at the top that directs users to the live webpage preview

## Benefits:

✅ Users can now see a beautifully formatted webpage instead of just the raw README
✅ The webpage is mobile-responsive and looks great on all devices
✅ Automatic deployment - whenever you update the main branch, the website updates too
✅ Professional appearance with gradient colors, hover effects, and clean typography
✅ All mod information is organized in clear, easy-to-read tables

## Preview:

The webpage includes:
- A striking header with gradient background
- Clear introduction section
- All mods organized by category (Quality of Life, Utilities, Gameplay Enhancements, etc.)
- Clickable links to each mod's CurseForge page
- Mobile-responsive design
- Footer with license information

**Important:** GitHub Pages must be enabled in repository settings (follow steps 1-4 above) before the automatic deployment will work. Once enabled, merge this PR to main, and GitHub Pages will automatically deploy your new website!
