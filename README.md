# Shopify Fee, ROAS & Break-Even Calculator (2026)

A free, single-file calculator for Shopify sellers. Pick your plan (Basic, Grow, Advanced,
Plus), enter one order, and it shows what Shopify actually keeps: the card percentage charged
on the order total including tax, the 30¢ fixed fee once per order, the +1% international
surcharge, a blended premium-card share, your COGS, packaging, shipping label and pick-pack —
then the break-even ROAS and POAS for the ads you are running.

- **Live page:** https://neo970720.github.io/shopify-fee-calculator/
- **No build step, no dependencies, no tracking.** `index.html` is the whole app.
- Rates: Shopify Payments **United States** published pricing, verified **20 November 2026**.

Built by Sheetwright. The paid companion, **Shopify True Profit OS** ($49, 10-sheet
Excel/Google Sheets workbook with 200 order rows, COGS by SKU, monthly ad allocation,
ROAS/POAS/break-even by month and by product, and a quarterly tax reserve), is at
https://sheetwrightstudio.gumroad.com/l/shopify-true-profit-os-2026

Not affiliated with, endorsed by, or sponsored by Shopify Inc. "Shopify" and "Shopify
Payments" are trademarks of Shopify Inc. The calculator is an estimate, not accounting or
tax advice.

## Local preview

Open `index.html` in a browser, or:

```
python3 -m http.server 8000
```

## Files

| File | Purpose |
|---|---|
| `index.html` | The calculator (HTML + CSS + JS in one file) |
| `_headers` | Optional header rules (used by Cloudflare Pages; ignored by GitHub Pages) |
| `robots.txt` | Allows all crawlers, points to the sitemap |
| `sitemap.xml` | Single-URL sitemap for Search Console / Bing |
| `.nojekyll` | Serve files as static assets, no Jekyll processing |
