# ParsaSec

The public site at [parsasec.com](https://parsasec.com), by
[@skydesperados](https://github.com/skydesperados).

The site currently publishes **Next.js Server Actions: Broken Access Control**.
It is plain HTML, CSS, and JavaScript, with no build step or external dependencies.
Bug 1 includes a theme-aware video player and an animated attacker-flow diagram.
The video, poster, and original GIF live in assets/. The original GIF is also
embedded in the HTML as a fallback.

## Publish changes

Edit index.html and any changed assets, review the page in a browser, then commit
and push to main.
GitHub Pages publishes from the repository root. The .nojekyll file disables
Jekyll processing, and CNAME declares the custom domain.

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
