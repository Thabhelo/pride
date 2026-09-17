# prideduve.de

Personal site for Pride Duve, in the style of karpathy.ai. Plain HTML and CSS, no build step.

## Edit

- `index.html` holds all content. `style.css` holds all styling.
- Photo is `assets/me.jpg` (from speculummundi.org). Timeline logos are `assets/logo-*.`
- Copy rule: no colons, semicolons or hyphens unless necessary (paper titles keep theirs). No em dashes.

## Preview

    python3 -m http.server 8000

## To confirm with Pride before launch

- He should be comfortable with his work email being public on the page.
- Logos belong to BNITM, UCT and NUST and are used only to identify the institutions.

## Hosting once prideduve.de is bought at GoDaddy

Simplest free route is GitHub Pages:

1. Push this folder to a GitHub repo, enable Pages on the main branch, set the custom domain to `prideduve.de`.
2. In GoDaddy DNS add A records for `@` to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153, and a CNAME for `www` to `<username>.github.io`.
3. Tick "Enforce HTTPS" in the Pages settings once the certificate is issued.

Cloudflare Pages works just as well: point the domain's nameservers at Cloudflare and attach the domain to the Pages project.
