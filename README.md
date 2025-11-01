# PullaPod Website

Static website for pullapod.app hosted on GitHub Pages.

## Deployment to GitHub Pages

To deploy this site to GitHub Pages:

1. Create a new repository on GitHub (e.g., `pullapod-site`)

2. Initialize git in this directory and push to GitHub:
   ```bash
   cd pullapod-site
   git init
   git add .
   git commit -m "Initial commit: PullaPod website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/pullapod-site.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select the `main` branch and `/ (root)` folder
   - Click "Save"

4. Your site will be available at `https://YOUR_USERNAME.github.io/pullapod-site/`

5. To use a custom domain (pullapod.app):
   - Add a `CNAME` file with your domain name
   - Configure DNS settings with your domain provider
   - Add your custom domain in GitHub Pages settings

## Local Development

To preview the site locally, you can use any static server. For example:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve
```

Then open `http://localhost:8000` in your browser.
