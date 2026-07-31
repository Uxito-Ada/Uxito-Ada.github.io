<<<<<<< HEAD
# Heyang Sun Homepage

This is a dependency-free static site for GitHub Pages. All content is in `index.html`, styling is in `styles.css`, and `assets/heyang-sun-cv.pdf` is the downloadable CV.

## Publish at `https://YOUR-USERNAME.github.io`

1. Create a new **public** GitHub repository named exactly `YOUR-USERNAME.github.io`. Replace `YOUR-USERNAME` with your GitHub account name.
2. In a terminal, change into this site directory and connect it to the repository:

   ```bash
   cd /root/heyang/personal-homepage
   git init
   git add .
   git commit -m "Publish personal homepage"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
   git push -u origin main
   ```

3. On GitHub, open the repository's **Settings** -> **Pages**. Under **Build and deployment**, select **Deploy from a branch**, then choose branch `main` and folder `/(root)`. Click **Save**.
4. GitHub will publish the site in a few minutes at `https://YOUR-USERNAME.github.io`.

## Optional custom domain

In **Settings** -> **Pages**, enter your custom domain and follow GitHub's DNS instructions. Enable **Enforce HTTPS** after DNS validation completes.

## Update the site

Edit `index.html` or `styles.css`, then publish the change:

```bash
git add .
git commit -m "Update homepage"
git push
```
=======
# Uxito-Ada.github.io
>>>>>>> 4335e3317a7c70c0bafcd48809058492ecac5d0c
