StumbleCorp Website — local static site

This folder contains a static website intended for publishing to GitHub Pages using a repo named `StumbleCorp.github.io` (replace `StumbleCorp` with your GitHub username or the desired owner name).

Files:
- `index.html` — main page
- `styles.css` — styling and layout

To publish to GitHub Pages (one-time steps):

1. Create a new repository on GitHub named `StumbleCorp.github.io` under your account (replace `StumbleCorp` with the chosen repo name if different).
2. In PowerShell, from this folder run:

```powershell
Set-Location "D:\rax coding\CorpWebsite"
# initialize if needed
git init
git remote add origin https://github.com/USERNAME/StumbleCorp.github.io.git
git add .
git commit -m "Initial StumbleCorp site"
git branch -M main
git push -u origin main
```

3. Wait a minute and visit `https://USERNAME.github.io` (replace `USERNAME` accordingly).

Notes:
- The top "Download (Discord)" and CTA buttons currently point to `https://discord.gg/YOUR_INVITE`. Replace `YOUR_INVITE` with your Discord invite code.
- If you want me to push these files to a remote repo for you, tell me the exact GitHub repo URL and whether you want me to create the `origin` remote and push.
