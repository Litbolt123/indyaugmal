# How to Host Your Website on GitHub Pages

## Step 1: Commit and Push Your Files

Since you already have a GitHub repository set up, you just need to add and commit your files:

```bash
git add index.html
git commit -m "Add professional homepage for IndyAugMal"
git push origin main
```

## Step 2: Enable GitHub Pages

1. Go to your GitHub repository: `https://github.com/[your-username]/indyaugmal`
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

## Step 3: Access Your Live Website

After a few minutes, your website will be live at:
**https://[your-username].github.io/indyaugmal/**

For example, if your username is `august`, it would be:
**https://august.github.io/indyaugmal/**

## Making Your Site Searchable on Google

### Option 1: Submit to Google Search Console (Recommended)
1. Go to [Google Search Console](https://search.google.com/search-console)
2. Add your property: `https://[your-username].github.io/indyaugmal`
3. Verify ownership (GitHub Pages sites are usually auto-verified)
4. Submit your sitemap (we can create one if needed)

### Option 2: Get Backlinks
- Share your website on social media
- List it in local business directories
- Add it to your LinkedIn profiles
- Share with Indianapolis business networks

### Option 3: Custom Domain (Optional)
If you want a custom domain like `indyaugmal.com`:
1. Purchase a domain from a registrar (Namecheap, Google Domains, etc.)
2. In GitHub Pages settings, add your custom domain
3. Update DNS records as instructed by GitHub

## Updating Your Website

Whenever you make changes:
1. Edit your files locally
2. Commit and push:
   ```bash
   git add .
   git commit -m "Update website"
   git push origin main
   ```
3. Changes will be live within 1-2 minutes

## Need Help?

- GitHub Pages Documentation: https://docs.github.com/en/pages
- Google Search Console: https://search.google.com/search-console

