# Triorra Looms

Handcrafted Indian ethnic wear — curated kurtis, 3-piece sets, anarkalis and tops.

## Live site
After enabling GitHub Pages, your site will be at:
`https://<your-username>.github.io/triorra-looms/`

## How to deploy

### Option A — GitHub Desktop (easiest)
1. Download and install [GitHub Desktop](https://desktop.github.com)
2. Click **File → New Repository**, name it `triorra-looms`, set the local path to this folder
3. Click **Publish repository** (keep it Public)
4. Go to your repo on github.com → **Settings → Pages**
5. Under *Source* choose **Deploy from a branch → main → / (root)** → Save
6. Your link will appear in ~1 minute ✨

### Option B — Command line
```bash
cd triorra-looms
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/triorra-looms.git
git push -u origin main
```
Then enable GitHub Pages in repo Settings → Pages.

## Folder structure
```
triorra-looms/
├── index.html      ← the website
└── images/         ← 22 product photos
    ├── product_01.jpg
    ├── product_02.jpg
    └── ...
```
