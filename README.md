# ImanQuest Privacy Policy — GitHub Pages

This folder contains the privacy policy page for the ImanQuest app. To get a **Privacy Policy URL** for App Store Connect:

## Steps

1. **Create a new repository on GitHub**
   - Go to [github.com/new](https://github.com/new)
   - Repository name: `imanquest-privacy` (or any name you like)
   - Public, no README (you're uploading this folder)
   - Create repository

2. **Push this folder to the repo**
   ```bash
   cd "/Users/kaleemahmed/Desktop/Tracking/cursor projects/ImanQuest/privacy-page"
   git init
   git add index.html README.md
   git commit -m "Add privacy policy page"
   git branch -M main
   git remote add origin https://github.com/YOUR_GITHUB_USERNAME/imanquest-privacy.git
   git push -u origin main
   ```
   Replace `YOUR_GITHUB_USERNAME` with your GitHub username.

3. **Enable GitHub Pages**
   - On the repo page: **Settings** → **Pages**
   - Under "Build and deployment", **Source**: Deploy from a branch
   - **Branch**: `main`, folder: `/ (root)` → Save
   - Wait a minute; your site will be at:
   **`https://YOUR_GITHUB_USERNAME.github.io/imanquest-privacy/`**

4. **Use in App Store Connect**
   - In App Store Connect → your app → **App Privacy**
   - Enter the URL: `https://YOUR_GITHUB_USERNAME.github.io/imanquest-privacy/`
   - Save

## Edit contact email

To change the contact email, edit `index.html` and replace `support@frsoftsolution.com` with your preferred address, then commit and push.
