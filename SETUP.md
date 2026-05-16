# GitHub Pages Deployment Guide

Your Jekyll portfolio is ready to deploy! Follow these steps:

## Step 1: Update Your Site Information

Edit `_config.yml` with your details:
- `title:` Your name or site name
- `author.name:` Your name
- `author.email:` Your email
- `url:` Your GitHub Pages URL (e.g., `https://yourusername.github.io`)
- `baseurl:` Keep as `/waypoint-website` for project site, or empty for user site

Edit `about.md` with your background and experience.

## Step 2: Test Locally (Optional but Recommended)

On Windows with Ruby installed:

```bash
cd waypoint-website
bundle install
bundle exec jekyll serve
```

Then open: http://localhost:4000

## Step 3: Push to GitHub

```bash
git add .
git commit -m "Initial Jekyll portfolio setup"
git push origin main
```

## Step 4: Enable GitHub Pages

1. Go to your GitHub repository
2. Click **Settings** → **Pages**
3. Under "Build and deployment":
   - **Source**: Select "Deploy from a branch"
   - **Branch**: Select your default branch (main/master)
   - **Folder**: Select `/ (root)`
4. Click **Save**

GitHub will automatically build and deploy your site!

## Step 5: View Your Site

- Check the **Actions** tab to see build progress
- Once complete, your site is live at:
  - User site: `https://yourusername.github.io`
  - Project site: `https://yourusername.github.io/waypoint-website`

## Next Steps

- Add blog posts to `_posts/` folder
- Customize `assets/css/style.css`
- Add images to `assets/images/`
- Create additional pages in root directory

## Troubleshooting

**Build fails?** Check the Actions tab for error details.

**Can't find Pages settings?** Make sure your repo is public or you have GitHub Pro.

**Changes not showing?** Clear browser cache or wait a few minutes for rebuild.

For more help, see the README.md
