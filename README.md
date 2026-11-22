# softmax — daily AI news for students

Live site: https://thesoftmax-site.thesoftmax.workers.dev

- `index.html` — website design (UI)
- `updates.js` — the news list (add new items at the top)
- `wrangler.jsonc` — Cloudflare settings (Worker name: thesoftmax-site)
- `.assetsignore` — files Cloudflare should not publish

Any change committed to `main` is built and deployed automatically by Cloudflare (Workers Builds).
