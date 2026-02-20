# Praxis Kushta Website
Static HTML website for Dott.ssa Irma Kushta.

## Local Development
To view the site locally, you can use any static file server. 
For example, using Python:
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000` in your web browser.

## Deployment to GitHub Pages
Since this is a standard HTML/CSS project without any build steps (like Node.js or Webpack), it is perfectly suited for GitHub Pages.

1. **Commit your changes**:
   ```bash
   git add .
   git commit -m "feat: Initial static site structure based on Web Archive"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Click on **Settings** > **Pages** (in the left sidebar).
   - Under **Build and deployment**, select **Deploy from a branch**.
   - Under **Branch**, select `main` (or `master`) and keep the folder as `/ (root)`.
   - Click **Save**.

3. **Wait a few minutes** for the GitHub Action to run, and your site will be available at `https://jitsejan.github.io/praxiskushta/` or your custom domain if configured. 

*If you are using a custom domain (`praxiskushta.de`), make sure to configure the Custom Domain section in Settings > Pages and add a `CNAME` file to the root of your repository.*
