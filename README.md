# ParsaSec

The public site at [parsasec.com](https://parsasec.com), by
[@skydesperados](https://github.com/skydesperados).

The home page lists writeups. Each title opens the full article on its own page.
The site uses plain HTML, CSS, and JavaScript, with no build step or external
dependencies.

- Home: index.html
- Article: writeups/nextjs-server-actions/index.html
- Article URL: https://parsasec.com/writeups/nextjs-server-actions/

Bug 1 includes a theme-aware video player and an animated attacker-flow diagram.
The video, poster, and original GIF live in assets/. The original GIF is also
embedded in the HTML as a fallback.

## Publish changes

Edit the home page, article, or assets, review the pages in a browser, then commit
and push to main. Old home-page section links redirect to the article.
GitHub Pages publishes from the repository root. The .nojekyll file disables
Jekyll processing, and CNAME declares the custom domain.

## Add a writeup

1. Create writeups/your-slug/index.html.
2. Add a list item to the writeup-list in the home page:

   ```html
   <li><a href="writeups/your-slug/">Your writeup title</a></li>
   ```

3. Add its public URL to sitemap.xml, then commit and push.

Only public site files belong in this repository. Keep research workspaces,
credentials, private evidence, and local backups outside it.

## Domain

- Apex: parsasec.com
- GitHub Pages DNS target: skydesperados.github.io
- A records at @: 185.199.108.153, 185.199.109.153,
  185.199.110.153, and 185.199.111.153
- www CNAME: skydesperados.github.io
- Domain ownership is verified for skydesperados on GitHub. Keep the
  _github-pages-challenge-skydesperados TXT record in DNS to retain verification.

See [GitHub's custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
