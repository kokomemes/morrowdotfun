# MORROW website

Static multipage site designed for GitHub Pages. Uses the original user-supplied MORROW logo at `assets/morrow-logo.png`. All background effects are CSS (not AI-generated images).

## Upload to GitHub Pages
Upload all five `.html` files plus the `assets/` folder to the repository root. In Settings → Pages, deploy from branch `main` and folder `/ (root)`. Do not upload the ZIP as a single file; extract first.

## Live data
Wallet, contract and network pages use read-only Ethereum JSON-RPC calls to public Ethereum and Base mainnet endpoints. No API keys or wallet permissions. Public RPC CORS policies, rate limits and availability may change; the UI reports errors instead of showing invented results. For production uptime, replace endpoints in `assets/app.js` with your own CORS-enabled RPC provider. This is not a security audit, and does not yet include Robinhood Chain because an authoritative endpoint has not been configured.

No framework or build step required. All UI text is English.
