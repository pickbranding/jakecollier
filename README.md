# jakecollier.co

Static personal site for Jake Collier, hosted on Cloudflare Pages.

- `site/` is what gets published (build output directory: `site`, no build command).
- Calendly links still use the `pickcreative` username; update them here if the username changes.
- Deployed as a Cloudflare Worker with static assets (`wrangler.jsonc` points at `site/`). Pushing to `main` deploys.
