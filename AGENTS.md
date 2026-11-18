# ilanapercher.com

A single-page resume site.

Follows global agent instructions in `~/.agents/AGENTS.md` unless this file says otherwise.

## Develop

Everything the site publishes is in `public/`. Run `npx wrangler dev` to serve it locally.

## Ship

- **Deploys by:** Workers Builds on the `ilanapercher-com` Worker: pushing to `main` deploys `public/`. Do not run `wrangler deploy` by hand.
- **Merge:** merge commits.
- **Check live:** `https://ilanapercher.com`, and an unknown path must answer 404. Branches get a preview URL, listed under the Worker's Previews in Cloudflare.
- **Checks:** none automated; run `npx wrangler dev` and look.
