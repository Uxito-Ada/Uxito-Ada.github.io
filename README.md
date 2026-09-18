# Heyang Sun Homepage

This is a dependency-free static site for GitHub Pages. All content is in `index.html` and styling is in `styles.css`.

## Public URL

After GitHub Pages is enabled for the `main` branch and `/(root)` folder, the site will be available at:

`https://uxito-ada.github.io`

## Enable GitHub Pages

In the GitHub repository, open **Settings** -> **Pages**. Under **Build and deployment**, select **Deploy from a branch**, then choose branch `main` and folder `/(root)`. Click **Save**.

## Optional custom domain

In **Settings** -> **Pages**, enter your custom domain and follow GitHub's DNS instructions. Enable **Enforce HTTPS** after DNS validation completes.

## Update the site

Edit `index.html` or `styles.css`, then publish the change:

```bash
git add .
git commit -m "Update homepage"
git push
```
