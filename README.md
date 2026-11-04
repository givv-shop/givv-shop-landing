# givv-shop-landing

Static GitHub Pages site for GIVV-SHOP's Black Friday and holiday push (repo `givv-shop/givv-shop-landing`). It has no build step and serves from the repo root, with `.nojekyll` included.

- `index.html` is the season hub with the timeline. The **Sets** section (three bundles at $529, $849 and $1,139) is in an HTML comment and stays disabled until the bundles are visible on givv-shop.com.
- `new-prices.html` covers clothing and jewelry price drops. It includes ItemList/Product JSON-LD with prices that match Wix as of Nov 4, 2026.
- `gift-guides/` holds **drafts, not yet approved**. They are noindex and not linked from the nav. I updated their prices to match live Wix.
- `assets/` holds the images, compressed to WebP and JPEG.
- Canonical tags point to https://www.givv-shop.com/, where purchases are made.
- `build.py` regenerates the pages from a live-price JSON export.

To publish: push to `main`, then go to Settings → Pages → Deploy from branch `main` / root.
