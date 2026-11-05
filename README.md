# givv-shop-landing

Static GitHub Pages site for GIVV-SHOP's Black Friday and holiday push (repo `givv-shop/givv-shop-landing`). It has no build step and serves from the repo root, with `.nojekyll` included.

- `index.html` is the season hub with the timeline. The **Black Friday Edit** section (`#sets`) is live, showing three Edits linked to their givv-shop.com product pages: The City Loafer Edit ($995), The Evening Emerald ($2,195) and The Weekend Knit ($929).
- `new-prices.html` covers clothing and jewelry price drops. It includes ItemList/Product JSON-LD with prices that match Wix as of Nov 4, 2026.
- `gift-guides/` holds the live buying guides (**Diamond gifts** and **Wide-leg denim**). They are indexable and linked from the site nav and the Gifting section on `index.html`.
- `assets/` holds the images, compressed to WebP and JPEG.
- Canonical tags point to https://www.givv-shop.com/, where purchases are made.
- `build.py` regenerates the pages from a live-price JSON export.

To publish: push to `main`, then go to Settings → Pages → Deploy from branch `main` / root.
