# CLAUDE.md

## Project Overview

Company website for **ByteApps LLC** (Denver, Colorado), hosted on GitHub
Pages under the ByteApps org, served at **byteapps.com** as the repo's
custom domain (CNAME file present; the app repos' Pages trees, e.g.
graffito's companion, serve under byteapps.com/<repo>/ paths).

- **Stack**: single-file `index.html`, inline CSS, no frameworks or build tools
- **Theme**: dark slate with the Graffito bitcoin-orange accent (`--accent: #c47a1a`)
- **Icons**: `assets/icons/*.svg` are the product/app icons (shared lineage
  with the app repos' icon pipeline); `assets/favicon.svg` is the ByteApps
  "B" mark

## History

Until 2026-08-14 this repo held Salvador Guerrero's personal portfolio; that
site moved (full git history preserved) to `ObjSal/ObjSal.github.io`
([objsal.github.io](https://objsal.github.io)). guerrero.vip should forward
there, byteapps.com here.

## Conventions

- Keep it one page, no dependencies, readable without JavaScript.
- The company legal name is exactly "ByteApps LLC" — it must match the
  Colorado SOS record, D&B (D-U-N-S 149902151), and the Apple/Google
  developer accounts. Contact email: contact@byteapps.com.
- Products list Graffito first; open-source Prime tools link to the ByteApps
  GitHub repos.
- The Graffito card carries the public beta links: TestFlight
  https://testflight.apple.com/join/WctNAbGu (iPhone + Mac) and the Play
  store listing https://play.google.com/store/apps/details?id=com.byteapps.graffito
  (Android open testing). Swap these for store links at 1.0 launch.

## Development

```bash
python3 -m http.server 8080  # then open http://localhost:8080
```
