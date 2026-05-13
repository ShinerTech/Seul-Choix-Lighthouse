# Great Lake Lighthouse

This is the static website for the Great Lake Lighthouse (Seul Choix Point Lighthouse), migrated and optimized for hosting on GitHub Pages.

## Deployment

This site consists of pure HTML, CSS, and asset files. It does not require a backend server. 

To deploy to GitHub Pages:
1. Push this repository to GitHub.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set the **Source** to `Deploy from a branch`.
4. Select the `main` (or `master`) branch and save.
5. GitHub will automatically build and deploy the site.

## Configuration

- `.nojekyll`: Present in the root directory to bypass Jekyll processing, ensuring files are served exactly as they are.
- `CNAME`: Configured for the custom domain (`www.greatlakelighthouse.com`).
- `sitemap.xml`: Contains the URL structure for search engine indexing.
- `robots.txt`: Search engine crawling instructions.

## Local Testing

You can test the site locally by running any static file server. For example, using Python:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your web browser.
