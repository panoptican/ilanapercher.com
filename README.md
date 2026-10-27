# ilanapercher.com

Single-page resume site for Ilana M. Percher.

## Deploy

```bash
npx wrangler pages deploy . --project-name ilanapercher-com
```

## Automatic Deploys (Cloudflare Pages Git Integration)

Connect this repository directly in Cloudflare Pages. Pushes to `main` then deploy automatically from Cloudflare.

Recommended Cloudflare Pages project settings for this repo:

- Framework preset: `None`
- Build command: *(leave empty)*
- Build output directory: `.`
