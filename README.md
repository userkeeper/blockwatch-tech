# blockwatch.tech

Marketing landing page for **Block Watch Shield** — an AI-powered Web3 signature review Chrome extension.

Hosted on GitHub Pages at https://blockwatch.tech.

## Stack

Pure static — single `index.html` with inline CSS/JS, plus images. No build step. No JS framework.
The `tokens.css` system inside `<style>` mirrors the design tokens used in the Block Watch Mini App so the look stays consistent.

## Local preview

```bash
# any static server works
npx serve .
# or
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

`git push` to `main`. GitHub Pages auto-publishes from the root of `main` to `blockwatch.tech` (via the `CNAME` file).

## Repository layout

```
.
├── index.html              # the entire landing page (CSS+JS inline)
├── CNAME                   # tells GitHub Pages to serve blockwatch.tech
├── logo.png
├── nav-shield.png
├── pay-stars.png, pay-ton.png
├── compatible-wallets.png
├── donate-*.png
└── img/                    # step-by-step mockups (EN/RU variants)
```

## Related

- Product code (private): https://github.com/userkeeper/block-watch
- Telegram bot: https://t.me/blockwatch_bot
- Chrome extension: (Web Store URL pending)
