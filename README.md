# GitHub Pages Starter for Yasna81

A minimal starter you can upload to a repo named `Yasna81.github.io` and submit to Google Search Console.

## Quick start
1. **Create repo:** On GitHub, create a public repo named exactly `Yasna81.github.io`.
2. **Upload files:** Upload everything from this folder to the repo root. Commit to `main`.
3. **Enable Pages:** Repo → Settings → Pages → Build and deployment → Source: `Deploy from a branch`, Branch: `main`, Folder: `/ (root)`.
4. **Turn on HTTPS:** Settings → Pages → check **Enforce HTTPS**.
5. **Replace placeholders:** In `index.html`, add the Google Search Console meta tag.
6. **Sitemap/robots:** Already configured for `yasna81.github.io`.
7. **Wait for publish:** After pushing, your site will be at `https://yasna81.github.io/`.

## Verify on Google Search Console
1. Go to Search Console and choose **URL prefix**. Enter `https://yasna81.github.io/`.
2. Choose **HTML tag** verification and copy the token.
3. Paste the meta tag inside `<head>` of `index.html`.
4. Commit & push. Visit your site to make sure the meta tag is visible in the page source.
5. Click **Verify** in Search Console.
6. Submit your `sitemap.xml` under **Sitemaps**.

### Alternative verification
- **HTML file upload:** Choose the HTML file method in Search Console, download the verification file and add it to the repo root. Commit, then verify.
- **DNS (if using custom domain):** If you use a custom domain, add a DNS TXT record with the provided token. Also add a `CNAME` file with your domain in the repo root and configure DNS `A`/`ALIAS` to GitHub Pages.

## Custom domain (optional)
- Create a file named `CNAME` in the repo root containing only your domain, e.g. `example.com`.
- In your DNS provider, add the following:
  - `A` records for `@` pointing to GitHub Pages IPs (check GitHub docs for the latest list).
  - `CNAME` record for `www` pointing to `Yasna81.github.io`.
- In **Settings → Pages**, set your custom domain and enable **Enforce HTTPS**.

## Tips
- Keep content fresh to help indexing.
- Use descriptive titles and meta descriptions in each page.
- Add more pages and list them in your `sitemap.xml`.
