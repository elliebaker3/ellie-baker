# ellie-baker.org

A one-page personal site — hand-written HTML and CSS, no build step, no dependencies.
Deployed with GitHub Pages at **https://ellie-baker.org**.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site. |
| `styles.css` | All styling. Light and dark themes via `prefers-color-scheme`. |
| `ellie.jpg` | Portrait, 512×512. |
| `CNAME` | Tells GitHub Pages the custom domain. Don't delete. |
| `.nojekyll` | Skips Jekyll processing. |

## Editing

Open `index.html` in a browser — no server needed. Every push to `main` redeploys
within about a minute.

## DNS

At Cloudflare. Four A records on `@` pointing at GitHub Pages
(`185.199.108.153`, `.109.153`, `.110.153`, `.111.153`) and a CNAME on `www`
pointing at `elliebaker3.github.io`.

These must be **DNS only** (grey cloud), not proxied — Cloudflare's proxy blocks
GitHub's certificate issuance.
