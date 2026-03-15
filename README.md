# Lanaoi Commissions Website

A clean, responsive Live2D rigging commission website for Lanaoi, rebuilt from [lanaoi.carrd.co](https://lanaoi.carrd.co/).

## Deploying to GitHub Pages

### 1. Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Name the repository (e.g., `lanaoi-commissions` or `<username>.github.io` for a user site)
3. Set it to **Public**
4. Click **Create repository**

### 2. Push the Code

```bash
cd d:\lanwebsite
git init
git add .
git commit -m "Initial commit - Lanaoi commission website"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/<REPO_NAME>.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**

Your site will be live at:
- `https://<YOUR_USERNAME>.github.io/<REPO_NAME>/`
- Or `https://<YOUR_USERNAME>.github.io/` if the repo is named `<username>.github.io`

## Structure

```
├── index.html       # Main website page
├── css/
│   └── style.css    # All styles
└── README.md        # This file
```

## Notes

- Images currently reference the original Carrd CDN. To self-host, download the images into an `images/` folder and update the `src` attributes.
- Fonts are loaded from Google Fonts (Sen, Bellota, Inter).
- No JavaScript dependencies — pure HTML & CSS.
