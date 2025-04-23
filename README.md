# Deploy to GitHub Pages

1. **Initialize a git repository (if not already):**
   ```sh
   git init
   git add index.html
   git commit -m "Initial commit"
   ```

2. **Create a new repository on GitHub** (e.g. `wedding-gift-page`).

3. **Add remote and push:**
   ```sh
   git remote add origin https://github.com/YOUR_USERNAME/wedding-gift-page.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages:**
   - Go to your repository on GitHub.
   - Click on "Settings" > "Pages" (or "Pages" in the sidebar).
   - Under "Source", select `main` branch and `/ (root)` folder.
   - Save.

5. **Access your site:**
   - The URL will be `https://YOUR_USERNAME.github.io/wedding-gift-page/`.

**Tip:** You can use a custom domain in the Pages settings if you want.
