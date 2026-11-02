# Necesories domain redirect

This small Vercel project permanently redirects requests to https://necesories.com,
preserving the path and query string (for example, /about?ref=tech).

## Deploy
1. Upload/import this folder as a new Vercel project, or deploy it with the Vercel CLI.
2. Add `necesories.tech` and `www.necesories.tech` under Project Settings -> Domains.
3. Configure the DNS records as Vercel instructs.
4. Redeploy after any changes.

`vercel.json` performs the primary server-side permanent redirect. `index.html` is a fallback.
