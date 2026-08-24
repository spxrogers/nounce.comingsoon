# skoop — coming soon

The static launch page served at https://skoop.la via GitHub Pages (branch `main`, root).

- `index.html` — one self-contained page: no external fonts, scripts, images, or analytics (privacy-first from day one).
- `CNAME` — custom domain for Pages.
- `.nojekyll` — serve files as-is.

DNS for `skoop.la` (apex): `A` records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` and `AAAA` to `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`; optional `www` → `CNAME spxrogers.github.io`. Turn on "Enforce HTTPS" in Pages settings once the certificate is issued.
