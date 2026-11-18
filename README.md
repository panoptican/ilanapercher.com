# ilanapercher.com

Single-page resume site for Ilana M. Percher.

## Deployment

The site is the Cloudflare Worker `ilanapercher-com`, set up in `wrangler.jsonc`. Cloudflare publishes only `public/`, at `ilanapercher.com`. The GitHub repository is connected through Workers Builds, so pushing to `main` deploys, and every other branch gets a preview URL.
