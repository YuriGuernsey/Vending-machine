# STOCK OS Public Demo

Static demonstration of STOCK's customer-facing vending experience. No real payment, account, stock database or motor control is present.

## Deploy to Cloudflare Pages

1. Create a new Cloudflare Pages project, select Direct Upload.
2. Upload the contents of this directory or the included ZIP.
3. Use the generated pages.dev URL to test.
4. Optionally connect a dedicated demo subdomain. Do not replace the existing meetatstock.com holding page unless you intend to.

The `_headers` file provides basic browser security headers on Cloudflare Pages.

## Development

Run `python3 -m http.server 8000` from this folder and open http://localhost:8000.

All sample inventory resets when reloading the page. There is no persistent storage or remote API.
