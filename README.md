# The Tactical Pause

A zero-dependency custom website for **thetacticalpause.com**. It is plain HTML/CSS, so Vercel has nothing to install or compile.

## Upload to GitHub

1. Open the repository you created on GitHub.
2. Choose **Add file → Upload files**.
3. Unzip the delivered package.
4. Upload `index.html`, `styles.css`, `vercel.json`, `robots.txt`, `sitemap.xml`, and this README.
5. Commit directly to the `main` branch.

## Deploy on Vercel

1. In Vercel, choose **Add New → Project**.
2. Import your GitHub repository.
3. Set **Framework Preset** to `Other` if Vercel does not detect it automatically.
4. Leave Build Command blank.
5. Leave Output Directory blank.
6. Click **Deploy**.

Every later commit to `main` will automatically update the live site.

## Connect Cloudflare domain

1. In the Vercel project, open **Settings → Domains**.
2. Add `thetacticalpause.com` and `www.thetacticalpause.com`.
3. Vercel will display the current DNS values it requires.
4. In Cloudflare, open **thetacticalpause.com → DNS → Records**.
5. Add or replace the records exactly as Vercel shows them.
6. For those Vercel records, initially select **DNS only** (gray cloud), not Proxied.
7. Return to Vercel and wait for both domains to show Valid Configuration.
8. Make one domain primary and redirect the other.

Vercel automatically issues the HTTPS certificate after DNS verification.

## Before launch

- The CTA currently emails `contact@thetacticalpause.com`. Change that address in `index.html` if needed.
- The Instagram button points to `@nerddisguisedasabro`.
- Add original photography and a finished logo in the next design pass.
- Add privacy/terms pages before collecting detailed personal or health information.
