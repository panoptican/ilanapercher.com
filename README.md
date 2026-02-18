# ilanapercher.com

Single-page resume site for Ilana M. Percher.

## Deploy

```bash
npx wrangler pages deploy . --project-name ilanapercher-com
```

## Automatic Deploys (GitHub Actions)

Pushes to `main` auto-deploy via `.github/workflows/deploy-pages.yml`.

Add these repository secrets in GitHub:

- `CLOUDFLARE_API_TOKEN` (Pages write permission)
- `CLOUDFLARE_ACCOUNT_ID` (Cloudflare account id)
