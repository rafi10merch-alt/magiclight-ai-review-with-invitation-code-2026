# MagicLight AI Review — Static Site

A single-page, honest review of MagicLight AI, built as a static site with no build step.

## Files in this package

- `index.html` — the full site (all HTML/CSS/JS in one file, no dependencies except Google Fonts)
- `robots.txt` — tells search engines they're allowed to crawl the site
- `sitemap.xml` — helps search engines discover the page (update the URL inside once you have a domain)
- `README.md` — this file

## Deploy on GitHub Pages (free, custom domain supported)

1. Create a new GitHub repo (e.g. `magiclight-review`).
2. Upload `index.html` (and `robots.txt`, `sitemap.xml` if you keep them) to the repo root.
3. Go to **Settings → Pages** in the repo.
4. Under **Source**, choose the `main` branch and `/ (root)` folder → **Save**.
5. Your site goes live at `https://<your-username>.github.io/<repo-name>/`.

## Optional: connect a custom domain (still free)

1. Buy a domain from any registrar (Namecheap, Porkbun, etc.).
2. In the repo, add a file named `CNAME` (no extension) containing just your domain, e.g.:
   ```
   www.yourdomain.com
   ```
3. At your domain registrar, add a CNAME record pointing `www` to `<your-username>.github.io`.
4. In **Settings → Pages**, enter the same domain and enable **Enforce HTTPS**.
5. Update the `<loc>` URL in `sitemap.xml` and the `Sitemap:` line in `robots.txt` to match your real domain.

## After it's live — submit it to Google

1. Go to [Google Search Console](https://search.google.com/search-console) and add your site (either the `github.io` URL or your custom domain).
2. Verify ownership (Search Console will walk you through this — usually a DNS record or an HTML file).
3. Submit your `sitemap.xml` URL under **Sitemaps**.
4. Use **URL Inspection** and click **Request Indexing** for your homepage.
5. This won't guarantee ranking, but it's the one step that actually tells Google the page exists — skipping it means waiting much longer to be found at all.

## Before you publish — a few honest notes

- The pricing figures in the Pricing section are reported third-party figures, not scraped live from MagicLight's site. Double-check current numbers before relying on them.
- The referral code and 5% figure reflect what was independently verifiable at the time of writing. If you swap in a different code, update the reality-check table so it stays accurate — that table is the page's main credibility asset.
- Consider adding real screenshots or a short demo clip once you've tested the tool yourself; genuine hands-on evidence will do more for rankings than any additional keyword coverage.
